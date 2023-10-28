# jc-mulesoft-industry-eapi
This is the solution for part-2 of the assignment where we have to implement 2 way ssl for our api

In a two-way SSL setup, a certificate is required from both the client and the server before they can establish a connection.
We are using self signed certificate.

In our scenario, our API functions as the server, and Postman serves as the REST client.

The server maintains a keystore containing its private key and digital certificate. Conversely, the server truststore holds the client's certificate, just as the client maintains its own certificate and server certificate.
<br/>
<br/>

As we see in below screenshot, both keystore and truststore needs to be configured.
![twoway1](https://github.com/TusharSrii/jc-mulesoft-industry-eapi/assets/60851515/a7e83521-1463-4df4-b137-fe0933406a83)

<br/>
<br/>

In postman we have to add the certificate as well.
![twowaypostman](https://github.com/TusharSrii/jc-mulesoft-industry-eapi/assets/60851515/5f8a5e4c-0a99-4073-b4a5-c2a00ee5eb4f)

<br/><br/>

We can see we are successfully able to access our api

![twoway](https://github.com/TusharSrii/jc-mulesoft-industry-eapi/assets/60851515/6dc6e8cd-be86-4144-80ab-364f4c64722d)


