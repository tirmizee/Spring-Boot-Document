# Spring-Boot-Document
คู่มือการใช้งาน

## Common Application properties

| Key      | Default value | Description |
| ------------- | ------------- |-------------|
| banner.charset  | UTF-8  |ใช้เพื่อตั้งค่าการเข้ารหัสไฟล์แบนเนอร์  |
| banner.location  | classpath:banner.txt  |It is used to set banner file location. |
| logging.file  |   |
| spring.application.index  |   |
| spring.application.name  |   |
| spring.application.admin.enabled  | FALSE  |
| spring.config.location  |   |
| spring.config.name  | application  |
| spring.mail.default-encoding  | UTF-8  |
| spring.mail.host  |   |
| spring.mail.password  |   |
| spring.mail.port  |   |
| spring.mail.test-connection  | FALSE  |
| spring.mail.username  |   |
| spring.main.sources  |   |
| server.address  |   |
| server.connection-timeout  |   |
| server.context-path  |   |
| server.port  | 8080  |
| server.server-header  |   |
| server.servlet-path  | /  |
| server.ssl.enabled  |   |
| spring.http.multipart.enabled  | TRUE  |
| spring.http.multipart.max-file-size  | 1MB  |
| spring.mvc.async.request-timeout  |   |
| spring.mvc.date-format  |   |
| spring.mvc.locale  |   |
| spring.social.facebook.app-id  |   |
| spring.social.linkedin.app-id  |   |
| spring.social.twitter.app-id  |   |
| security.basic.authorize-mode  | role  |
| security.basic.enabled  | TRUE  |

## 1. Core properties

| Key      | Default value | Description |
| ------------- | ------------- |-------------|
| debug  | FALSE  |
| info.*  |   |
| logging.config  |   |
| logging.exception-conversion-word  | %wEx  |
| logging.file.clean-history-on-start  | FALSE  |
| logging.file.max-history  | 7  |
| logging.file.max-size  | 10MB  |
| logging.file.name  |   |
| logging.file.path  |   |
| logging.file.total-size-cap  | 0B  |
| logging.group.*  |   |
| logging.level.*  |   |
| logging.pattern.console  | %clr(%d{${LOG_DATEFORMAT_PATTERN:-yyyy-MM-dd HH:mm:ss.SSS}}){faint} %clr(${LOG_LEVEL_PATTERN:-%5p}) %clr(${PID:- }){magenta} %clr(---){faint} %clr([%15.15t]){faint} %clr(%-40.40logger{39}){cyan} %clr(:){faint} %m%n${LOG_EXCEPTION_CONVERSION_WORD:-%wEx}  |
| logging.pattern.dateformat  | yyyy-MM-dd HH:mm:ss.SSS  |
| logging.pattern.file  | %d{${LOG_DATEFORMAT_PATTERN:-yyyy-MM-dd HH:mm:ss.SSS}} ${LOG_LEVEL_PATTERN:-%5p} ${PID:- } --- [%t] %-40.40logger{39} : %m%n${LOG_EXCEPTION_CONVERSION_WORD:-%wEx}  |
| logging.pattern.level  | %5p  |
| logging.pattern.rolling-file-name  | ${LOG_FILE}.%d{yyyy-MM-dd}.%i.gz  |
| logging.register-shutdown-hook  | FALSE  |
| spring.aop.auto  | TRUE  |
| spring.aop.proxy-target-class  | TRUE  |
| spring.application.admin.enabled  | FALSE  |
| spring.application.admin.jmx-name  | org.springframework.boot:type=Admin,name=SpringApplication  |
| spring.application.name  |   |
| spring.autoconfigure.exclude  |   |
| spring.banner.charset  | UTF-8  |
| spring.banner.image.bitdepth  | 4  |
| spring.banner.image.height  |   |
| spring.banner.image.invert  | FALSE  |
| spring.banner.image.location  | classpath:banner.gif  |
| spring.banner.image.margin  | 2  |
| spring.banner.image.pixelmode  | TEXT  |
| spring.banner.image.width  | 76  |
| spring.banner.location  | classpath:banner.txt  |
| spring.beaninfo.ignore  | TRUE  |
| spring.codec.max-in-memory-size  |   |
| spring.config.additional-location  |   |
| spring.config.location  |   |
| spring.config.name  | application  |
| spring.info.build.encoding  | UTF-8  |
| spring.info.build.location  | classpath:META-INF/build-info.properties  |
| spring.info.git.encoding  | UTF-8  |
| spring.info.git.location  | classpath:git.properties  |
| spring.jmx.default-domain  |   |
| spring.jmx.enabled  | FALSE  |
| spring.jmx.server  | mbeanServer  |
| spring.jmx.unique-names  | FALSE  |
| spring.main.allow-bean-definition-overriding  | FALSE  |
| spring.main.banner-mode  | console  |
| spring.main.lazy-initialization  | FALSE  |
| spring.main.log-startup-info  | TRUE  |
| spring.main.register-shutdown-hook  | TRUE  |
| spring.main.sources  |   |
| spring.main.web-application-type  |   |
| spring.mandatory-file-encoding  |   |
| spring.messages.always-use-message-format  | FALSE  |
| spring.messages.basename  | messages  |
| spring.messages.cache-duration  |   |
| spring.messages.encoding  | UTF-8  |
| spring.messages.fallback-to-system-locale  | TRUE  |
| spring.messages.use-code-as-default-message  | FALSE  |
| spring.output.ansi.enabled  | detect  |
| spring.pid.fail-on-write-error  |   |
| spring.pid.file  |   |
| spring.profiles  |   |
| spring.profiles.active  |   |
| spring.profiles.include  |   |
| spring.quartz.auto-startup  | TRUE  |
| spring.quartz.jdbc.comment-prefix  | #, --  |
| spring.quartz.jdbc.initialize-schema  | embedded  |
| spring.quartz.jdbc.schema  | classpath:org/quartz/impl/jdbcjobstore/tables_@@platform@@.sql  |
| spring.quartz.job-store-type  | memory  |
| spring.quartz.overwrite-existing-jobs  | FALSE  |
| spring.quartz.properties.*  |   |
| spring.quartz.scheduler-name  | quartzScheduler  |
| spring.quartz.startup-delay  | 0s  |
| spring.quartz.wait-for-jobs-to-complete-on-shutdown  | FALSE  |
| spring.reactor.debug-agent.enabled  | TRUE  |
| spring.task.execution.pool.allow-core-thread-timeout  | TRUE  |
| spring.task.execution.pool.core-size  | 8  |
| spring.task.execution.pool.keep-alive  | 60s  |
| spring.task.execution.pool.max-size  |   |
| spring.task.execution.pool.queue-capacity  |   |
| spring.task.execution.shutdown.await-termination  | FALSE  |
| spring.task.execution.shutdown.await-termination-period  |   |
| spring.task.execution.thread-name-prefix  | task-  |
| spring.task.scheduling.pool.size  | 1  |
| spring.task.scheduling.shutdown.await-termination  | FALSE  |
| spring.task.scheduling.shutdown.await-termination-period  |   |
| spring.task.scheduling.thread-name-prefix  | scheduling-  |
| trace  | FALSE  |

