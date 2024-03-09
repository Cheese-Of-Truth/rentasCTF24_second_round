# rentasCTF24_second_round
## Name: I Hope You Have The Software
## Category: Network
## Description:
![chal](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/2c6299c0-81b2-44e1-bcc1-23a6af12e71e)

## Walkthrough:

A .pkt file is provided. As I learnt Cisco before, so I know that I have to open with cisco packet tracer

![overallpic](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/d32ef53d-20c9-4539-8385-7a05a927b958)

Above is the overall view of the pkt file. I have briefly checked all of the devices, not much thing has been configured except the http service of the servers.

![withoutflag](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/23054a07-2a7e-4928-a10c-d1483d4fcf9d)

The picture above has shown the default files in the service. 

![wrongindex](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/beec6743-9fb9-47d2-9c8e-06f968e61460)
The above is the default value of index.html

In server 18, we can see that there is only one file which is index.html
![correct_index](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/3c6dc0bc-bef0-4da8-adb6-dcb77dfdbab9)


Open in, I saw some suspicious spam
![correctwithoutflag](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/d88feedb-a371-4c4f-a4e2-bec809df41d9)

Scroll down abit, I saw the flag
![scroll lower](https://github.com/Cheese-Of-Truth/rentasCTF24_second_round/assets/145131434/c291d0cb-54bb-468b-90e0-4d64a087029a)

FLAG: RWSC{!t5_a_t4c3r_f!l3_:D}
