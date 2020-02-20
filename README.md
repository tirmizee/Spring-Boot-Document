# Spring-Boot-Document
ทบทวนเนื้อหา Spring Boot

### Common Application properties

| Key      | Default value | Description |
| ------------- | ------------- |-------------|
| banner.charset  | UTF-8  |ใช้เพื่อตั้งค่าการเข้ารหัสไฟล์แบนเนอร์  |
| banner.location  | classpath:banner.txt  |It is used to set banner file location. |


### Multiple Eclude

- in application.property

      spring.autoconfigure.exclude[0]=org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration
      spring.autoconfigure.exclude[1]=org.springframework.boot.autoconfigure.security.servlet.SecurityAutoConfiguration
      
- in class config

      @SpringBootApplication(exclude = {
        DataSourceAutoConfiguration.class,
        SecurityAutoConfiguration.class
      })
      public class SpringBootJApplication {
        public static void main(String[] args) {
          SpringApplication.run(SpringBootJApplication.class, args);
        }
      }

### Annotation Conditional

## Reference

- https://docs.spring.io/spring-boot/docs/current/reference/html/howto.html#howto-data-access
