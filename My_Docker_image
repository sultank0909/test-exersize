FROM openjdk:11
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac Main.java
RUN java Main > Main.html

FROM nginx
COPY --from=0 /usr/src/myapp/Main.html /usr/share/nginx/html/index.html
