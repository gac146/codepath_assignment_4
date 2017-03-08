# Project 5 - Encryption

Time spent: 7 hours spent in total

## User Stories

The following **required** functionality is completed:

1\. Symmetric Encrypt/Decrypt
  * [x]  Required: Repair the symmetric encrypt and decrypt code

2\. Encrypted Message 1
  * [x]  Required: Decrypt the government message
  * [x]  Required: Encrypt a response and include in this README
  * ENCRYPTED RESPONSE: XONYaD62F3iBl0uP9/KpivRdtU/cjvpBzskpFgGrsxXe7s90qjj2vbswlMO6ZPaCjWWcTyZr8rjd3eKE+oqKUOC8qWJH5A2LQQylb4ey7eA6SFip5B+ssEaOx3i+hSQu
    KEY: secretkey
    NOTE: I just used the symmetric encryption for this question because I don't know who the receiver is.

3\. Generate Public-Private Keys
  * [x]  Required: Repair the key generator code
  * [x]  Required: Generate keys for "johnsteed" and add him to the Agent Directory

4\. Asymmetric Encrypt/Decrypt
  * [x]  Required: Repair the asymmetric encrypt and decrypt code

5\. Create/Verify Signature
  * [x]  Required: Repair the create and verify signature code
  
6\. Encrypted Message 2
  * [x]  Required: Decrypt the message
  * [x]  Required: Verify the message
  * [x]  Required: Include a response message in this README
  * ENCRYPTED RESPONSE:
    
	To: sidneybristow
	
	From: agent99

 	Body: a2kKKBv9f0w+ivZT8X9SrtbZ1tVsUWYhAT1zy4MYwCM2UjGrn5On0FRcLsB/mLBaiU+jTL49lMV1OQd0gWaskn1XPOASllD2dtYK6GfKqia3xR+wCePg7W4xui3w9YE9aP/QjJZLWoIjgSMvJict/4wJQshLKsfa6ByYWKvhAbVQXahkhixkM4Yfhf4wQ2lSqAvL89B7mKkFcmuIEjO6kbQ3w6jFKhlKdGNk5SIgWfDzLLVhBZ+SZWzsvgKu5NTtZx+RtnIMc9VjsnkwL3yCo8uJMole/WXime+zZTkjZ0crhEcuu5kw46Nw+Knk3H2MUfR8C0Rx6oNxtNdwiIhzog==

	Signature: oq/UYMblqHPxwuTVlTUHJiC0M2Y8FdCr/Svznucpq6AE6N+nZmXbimD4zmYBy31REiWzARHTuK0/ul3BmtNMAoZWoCUxPmNX8VKpHwANrRSCs5Bhxp3OvckLGCOSHDpy+yVWHFnnXpu6wRmobTA14hYsn7BUg7MBqv2zAAo+ah2ZwhuUpzuQgiwdp55X+2zWS1ivs8bZAdcv1kf1XKcMDjEp13SYyUjqzxgQ9mIIvin18LIdmT/R8j4oxcoiEhnfTYJ+BOCiGdO0KYQqoEs8Ckr96CX/QbDHgVBAluXU4CCgBWLtHjqFQ2Ahszvl7qGssksIF75x37c7UqEOGkUABA==
	

7\. Agent Messages
  * [x]  Required: Repair the dropbox code
  * [x]  Required: Repair the messages area
  * [x]  Required: Display encrypted messages for all agents
  * [x]  Required: Messages indicate whether the message signature is valid
  * [x]  Required: Your messages are automatically decrypted

8\. Identify the Double Agent
  * [x]  Required: Decrypt as many email messages as possible
  * [x]  Required: Identify the double agent: __natasha____________

The following objectives are **optional**:

* Bonus Objective 1\.
  * [x]  Track down the bugs in the code and fix them.

* Bonus Objective 2\.
  * [ ]  Write a report of your discoveries (longer than 300 characters).
  * [ ]  Compose a secure email for sending over an insecure network.
  * [ ]  Include the email with your encrypted report in this README.

* Bonus Objective 3\.
  * [ ]  Add a "Create/Verify Checksum" section to the Encryption Tools area.

* Advanced Objective 1\.
  * [ ]  Add support for other symmetric algorithms.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/pKyAKLh.gifv' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I am on a Windows machine and I had to set an environmental variable OPENSSL_CONF = C:\xampp\apache\conf\openssl.cnf
I kept getting errors and I thought there was something wrong with my code. It took me a while to find the solution.

## License

    Copyright [2017] [Gustavo Carbone]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.