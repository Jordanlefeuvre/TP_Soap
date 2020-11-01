# TP_Soap

Projet non fini, avec des erreurs de ce type : 
```
2020-11-01 13:00:59.176 ERROR 8328 --- [nio-8080-exec-1] a.c.c.C.[.[.[.[messageDispatcherServlet] : Servlet.service() for servlet [messageDispatcherServlet] in context with path [] threw exception [Request processing failed; nested exception is java.lang.Error: Unresolved compilation problems: 
    Type mismatch: cannot convert from com.ynov.nantes.soap.author.Author to com.ynov.nantes.soap.entity.Author
    The method setAuthor(com.ynov.nantes.soap.author.Author) in the type AddAuthorResponse is not applicable for the arguments (com.ynov.nantes.soap.entity.Author)
] with root cause

java.lang.Error: Unresolved compilation problems: 
    Type mismatch: cannot convert from com.ynov.nantes.soap.author.Author to com.ynov.nantes.soap.entity.Author
    The method setAuthor(com.ynov.nantes.soap.author.Author) in the type AddAuthorResponse is not applicable for the arguments (com.ynov.nantes.soap.entity.Author)
```

 # Postman
 
URL: 127.0.0.1:8080/ws/
body exemple:
```
 <soapenv:Envelope
    xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
    xmlns:ynov="http://nantes.ynov.com/soap/author">
    <soapenv:Header />
    <soapenv:Body>
        <ynov:addAuthorRequest>
            <ynov:firstname>John</ynov:firstname>
            <ynov:firstname>Doe</ynov:firstname>
        </ynov:addAuthorRequest>
    </soapenv:Body>
</soapenv:Envelope>
```
