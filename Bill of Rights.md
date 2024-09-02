## 3. Start up your web browser, and make sure your browser’s cache is cleared, as discussed above.

1. Start up the Wireshark packet sniffer
2. Enter the following URL into your browser
http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file3.html
Your browser should display the rather lengthy US Bill of Rights.
3. Stop Wireshark packet capture and enter “http” in the display-filter-specification window, so that only captured HTTP messages will be displayed.

## Answer the following questions:

### 1. How many HTTP GET request messages did your browser send? Which packet number in the trace contains the GET message for the Bill or Rights?

![image](https://github.com/user-attachments/assets/0a02d03c-777c-48a7-ba8c-a7c544e311fb)
### ```My browser sent two HTTP GET requests to the server.```
One request for the file contained in the server and one request for the favicon icon for the webpage.

### ```Packet number 6939 contains the GET message for the Bill of Rights.```

## 2. Which packet number in the trace contains the status code and phrase associated with the response to the HTTP GET request?

![image](https://github.com/user-attachments/assets/63e1da1e-7548-463d-9ffe-bc420eb947cf)
### ```Packet number 7257 contains the HTTP response – Bill of Rights.```

## 3. What is the status code and phrase in the response?

![image](https://github.com/user-attachments/assets/95beeff0-3332-4013-91d3-b23f1b9a4a63)
### ```The status code and descriptor for the corresponding response is 200 [OK].```

## 4. How many data-containing TCP segments were needed to carry the single HTTP response and the text of the Bill of Rights?

![image](https://github.com/user-attachments/assets/a83f2a75-326a-46e2-85d8-d62292b98693)
### ```Four TCP segments were needed to carry the single HTTP response containing the Bill of Rights.```





