Spring tutorial https://spring.io/guides/gs/producing-web-service/

1. Start Application.
2. $ curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws \
    | tidy -xml -i -q
