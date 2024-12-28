# 前端

## Check Env:

node -v

npm -v

npm install pnpm -g

pnpm -v

cd /d "E:\Jimmy\Code\OpenSource\JeecgBoot\jeecgboot-vue3"

**pnpm i**

## Test Env:

pnpm dev

http://localhost:3100/dashboard/analysis

# 后端

## 配置私服

### JDK

JAVA_HOME: "C:\Program Files\Java\jdk-17"

%JAVA_HOME%\bin

%JAVA_HOME%\jre\bin

### MAVEN

MAVEN_HOME: "C:\Java\apache-maven-3.9.9"

添加以下内容到（ C:\Java\apache-maven-3.9.9\conf\settings.xml ）

`<mirror>`
    `<id>`nexus-aliyun `</id>`
    `<mirrorOf>`*,!jeecg,!jeecg-snapshots,!getui-nexus `</mirrorOf>`
    `<name>`Nexus aliyun `</name>`
    `<url>`http://maven.aliyun.com/nexus/content/groups/public `</url>`
`</mirror>`

### MYSQL & REDIS


### BUILD & START

cd /d "E:\Jimmy\Code\OpenSource\JeecgBoot\jeecg-boot\"

mvn -v

mvn install

cd /d "E:\Jimmy\Code\OpenSource\JeecgBoot\jeecg-boot\jeecg-module-system\jeecg-system-start\target"

java -jar jeecg-system-start-3.7.2.jar

http://localhost:8080/jeecg-boot/#/home
