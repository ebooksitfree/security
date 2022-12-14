![Cover image for Network Security with OpenSSL](https://imgdetail.ebookreading.net/cover/cover/security/EB059600270X.jpg)

[Network Security with OpenSSL](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_1.html "Network Security with OpenSSL")
====================================================================================================================

Author : [Pravir Chandra](https://ebookreading.net/search/author/Pravir+Chandra),[ Matt Messier](https://ebookreading.net/search/author/+Matt+Messier),[ John Viega](https://ebookreading.net/search/author/+John+Viega)

Release Date : 2002/06/01

ISBN : 059600270X

Topic : [Security](https://ebookreading.net/search/category/security)

Book Description
-----------------

Most applications these days are at least somewhat network aware, but how do you protect those applications against common network security threats?  Many developers are turning to OpenSSL, an open source version of SSL/TLS, which is the most widely used protocol for secure network communications.The OpenSSL library is seeing widespread adoption for web sites that require cryptographic functions to protect a broad range of sensitive information, such as credit card numbers and other financial transactions. The library is the only free, full-featured SSL implementation for C and C++,  and it can be used programmatically or from the command line to secure most TCP-based network protocols.Network Security with OpenSSL enables developers to use this protocol much more effectively. Traditionally, getting something simple done in OpenSSL could easily take weeks.   This concise book gives you the guidance you need to avoid pitfalls, while allowing you to take advantage of the library?s advanced features.   And, instead of bogging you down in the technical details of how SSL works under the hood, this book provides only the information that is necessary to use OpenSSL safely and effectively.  In step-by-step fashion, the book details the challenges in securing network communications, and shows you how to use OpenSSL tools to best meet those challenges.As a system or network administrator, you will benefit from the thorough treatment of the OpenSSL command-line interface, as well as from step-by-step directions for obtaining certificates and setting up your own certification authority.  As a developer, you will further benefit from the in-depth discussions and examples of how to use OpenSSL in your own programs.  Although OpenSSL is written in C, information on how to use OpenSSL with Perl, Python and PHP is also included.OpenSSL may well answer your need to protect sensitive data. If that?s the case, Network Security with OpenSSL is the only guide available on the subject.
              
Table of Contents
-----------------

1. [Dedication](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_3.html)
1. [A Note Regarding Supplemental Files](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_4.html)
1. [Preface](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_5.html)
    1. [About This Book](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_5.html#openssl-PREF-SECT-1)
    1. [Conventions Used in This Book ](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_5.html#openssl-PREF-SECT-2)
    1. [Comments and Questions ](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_5.html#openssl-PREF-SECT-3)
    1. [Acknowledgments](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_5.html#openssl-PREF-SECT-4)
1. [1. Introduction](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html)
    1. [1.1. Cryptography for the Rest of Us](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.1.1. Goals of Cryptography](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.1.2. Cryptographic Algorithms](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
            1. [1.1.2.1. Symmetric key encryption](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
            1. [1.1.2.2. Public key encryption](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
            1. [1.1.2.3. Cryptographic hash functions and Message Authentication Codes](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
            1. [1.1.2.4. Digital signatures](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
    1. [1.2. Overview of SSL](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
    1. [1.3. Problems with SSL](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.3.1. Efficiency](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
            1. [1.3.1.1. Cryptographic acceleration hardware](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
            1. [1.3.1.2. Load balancing](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.3.2. Keys in the Clear](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.3.3. Bad Server Credentials](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.3.4. Certificate Validation](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.3.5. Poor Entropy](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.3.6. Insecure Cryptography](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
    1. [1.4. What SSL Doesn???t Do Well](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.4.1. Other Transport Layer Protocols](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.4.2. Non-Repudiation](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.4.3. Protection Against Software Flaws](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.4.4. General-Purpose Data Security](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
    1. [1.5. OpenSSL Basics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
    1. [1.6. Securing Third-Party Software](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.6.1. Server-Side Proxies](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
        1. [1.6.2. Client-Side Proxies](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_6.html#openssl-CHP-1-SECT-)
1. [2. Command-Line Interface](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html)
    1. [2.1. The Basics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.1.1. Configuration Files](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
    1. [2.2. Message Digest Algorithms](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.2.1. Examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
    1. [2.3. Symmetric Ciphers](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.3.1. Examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
    1. [2.4. Public Key Cryptography](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.4.1. Diffie-Hellman](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
            1. [2.4.1.1. Examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.4.2. Digital Signature Algorithm](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
            1. [2.4.2.1. Examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.4.3. RSA](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
            1. [2.4.3.1. Examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
    1. [2.5. S/MIME](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
        1. [2.5.1. Examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
    1. [2.6. Passwords and Passphrases](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
    1. [2.7. Seeding the Pseudorandom Number Generator](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_7.html#openssl-CHP-2-SECT-)
1. [3. Public Key Infrastructure (PKI)](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html)
    1. [3.1. Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.1.1. Certification Authorities](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
            1. [3.1.1.1. Private Certification Authorities](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
            1. [3.1.1.2. Public Certification Authorities](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.1.2. Certificate Hierarchies](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.1.3. Certificate Extensions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.1.4. Certificate Revocation Lists](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.1.5. Online Certificate Status Protocol](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
    1. [3.2. Obtaining a Certificate](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.2.1. Personal Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.2.2. Code-Signing Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.2.3. Web Site Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
    1. [3.3. Setting Up a Certification Authority](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.3.1. Creating an Environment for Your Certification Authority](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.3.2. Building an OpenSSL Configuration File](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.3.3. Creating a Self-Signed Root Certificate](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.3.4. Issuing Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
        1. [3.3.5. Revoking Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_8.html#openssl-CHP-3-SECT-)
1. [4. Support Infrastructure](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html)
    1. [4.1. Multithread Support](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.1.1. Static Locking Callbacks](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.1.2. Dynamic Locking Callbacks](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
    1. [4.2. Internal Error Handling](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.2.1. Manipulating Error Queues](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.2.2. Human-Readable Error Messages](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.2.3. Threading and Practical Applications](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
    1. [4.3. Abstract Input/Output](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.3.1. Source/Sink BIOs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
            1. [4.3.1.1. Memory sources/sinks](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
            1. [4.3.1.2. File sources/sinks](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
            1. [4.3.1.3. Socket sources/sinks](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
            1. [4.3.1.4. BIO pairs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.3.2. Filter BIOs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
    1. [4.4. Random Number Generation](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.4.1. Seeding the PRNG](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.4.2. Using an Alternate Entropy Source](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
    1. [4.5. Arbitrary Precision Math](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.5.1. The Basics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.5.2. Mathematical Operations](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
        1. [4.5.3. Generating Prime Numbers](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
    1. [4.6. Using Engines](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_9.html#openssl-CHP-4-SECT-)
1. [5. SSL/TLS Programming](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html)
    1. [5.1. Programming with SSL](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.1.1. The Application(s) to Secure](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.1.2. Step 1: SSL Version Selection and Certificate Preparation](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.2.1. Background ](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.2.2. Certificate preparation](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.2.3. Our example extended](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.1.3. Step 2: Peer Authentication](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.3.1. Background](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.3.2. Incorporating trusted certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.3.3. Certificate verification](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.3.4. Incorporating certificate revocation lists](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.3.5. Post-connection assertions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.3.6. Further extension of the examples](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.1.4. Step 3: SSL Options and Cipher Suites](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.4.1. Setting SSL options](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.4.2. Ephemeral keying](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.4.3. Cipher suite selection](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.4.4. The final product](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.1.4.5. Beyond the example](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
    1. [5.2. Advanced Programming with SSL](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.2.1. SSL Session Caching](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.1.1. Client-side SSL sessions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.1.2. Server-side SSL sessions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.1.3. An on-disk, session caching framework](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.2.2. I/O on SSL Connections](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.2.1. Reading and writing functions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.2.2. Blocking I/O](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.2.3. Non-blocking I/O](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
        1. [5.2.3. SSL Renegotiations](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.3.1. Implementing renegotiations](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.3.2. Renegotiations in 0.9.7](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
            1. [5.2.3.3. Further notes](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_10.html#openssl-CHP-5-SECT-)
1. [6. Symmetric Cryptography](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html)
    1. [6.1. Concepts in Symmetric Cryptography](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.1.1. Block Ciphers and Stream Ciphers](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.1.2. Basic Block Cipher Modes](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
    1. [6.2. Encrypting with the EVP API](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.2.1. Available Ciphers](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.1. AES](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.2. Blowfish](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.3. CAST5](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.4. DES](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.5. DESX](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.6. Triple DES](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.7. IDEA](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.8. RC2???](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.9. RC4???](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
            1. [6.2.1.10. RC5???](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.2.2. Initializing Symmetric Ciphers](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.2.3. Specifying Key Length and Other Options](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.2.4. Encryption](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.2.5. Decryption](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
        1. [6.2.6. Handling UDP Traffic with Counter Mode](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
    1. [6.3. General Recommendations](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_11.html#openssl-CHP-6-SECT-)
1. [7. Hashes and MACs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html)
    1. [7.1. Overview of Hashes and MACs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
    1. [7.2. Hashing with the EVP API](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
    1. [7.3. Using MACs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
        1. [7.3.1. Other MACs](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
            1. [7.3.1.1. CBC-MAC](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
            1. [7.3.1.2. XCBC-MAC](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
            1. [7.3.1.3. XOR-MAC](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
            1. [7.3.1.4. UMAC](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
    1. [7.4. Secure HTTP Cookies](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_12.html#openssl-CHP-7-SECT-)
1. [8. Public Key Algorithms](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html)
    1. [8.1. When to Use Public Key Cryptography](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
    1. [8.2. Diffie-Hellman](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.2.1. The Basics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.2.2. Generating and Exchanging Parameters](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.2.3. Computing Shared Secrets](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.2.4. Practical Applications](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
    1. [8.3. Digital Signature Algorithm (DSA)](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.3.1. The Basics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.3.2. Generating Parameters and Keys](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.3.3. Signing and Verifying ](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.3.4. Practical Applications](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
    1. [8.4. RSA](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.4.1. The Basics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.4.2. Generating Keys](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.4.3. Data Encryption, Key Agreement, and Key Transport](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.4.4. Signing and Verifying](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.4.5. Practical Applications](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
    1. [8.5. The EVP Public Key Interface](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.5.1. Signing and Verifying](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.5.2. Encrypting and Decrypting](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
    1. [8.6. Encoding and Decoding Objects](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.6.1. Writing and Reading DER-Encoded Objects](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
        1. [8.6.2. Writing and Reading PEM-Encoded Objects](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_13.html#openssl-CHP-8-SECT-)
1. [9. OpenSSL in Other Languages](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html)
    1. [9.1. Net::SSLeay for Perl](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.1.1. Net::SSLeay Variables](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.1.2. Net::SSLeay Error Handling](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.1.3. Net::SSLeay Utility Functions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.1.4. Net::SSLeay Low-Level Bindings](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
    1. [9.2. M2Crypto for Python](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.2.1. Low-Level Bindings](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.2.2. High-Level Classes](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.2.1. M2Crypto.SSL](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.2.2. M2Crypto.BIO](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.2.3. M2Crypto.EVP](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.2.4. Miscellaneous crypto](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.2.3. Python Module Extensions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.3.1. Extensions to httplib: httpslib](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.3.2. Extensions to urllib: m2urllib](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
            1. [9.2.3.3. Extensions to xmlrpclib: m2xmlrpclib](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
    1. [9.3. OpenSSL Support in PHP](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.3.1. General Functions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.3.2. Certificate Functions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.3.3. Encryption and Signing Functions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
        1. [9.3.4. PKCS#7 (S/MIME) Functions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_14.html#openssl-CHP-9-SECT-)
1. [10. Advanced Programming Topics](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html)
    1. [10.1. Object Stacks](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
    1. [10.2. Configuration Files](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
    1. [10.3. X.509](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.3.1. Generating Requests](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
            1. [10.3.1.1. Subject name](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
            1. [10.3.1.2. X.509 Version 3 extensions](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
            1. [10.3.1.3. Putting it all together](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.3.2. Making Certificates](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.3.3. X.509 Certificate Checking](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
    1. [10.4. PKCS#7 and S/MIME](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.4.1. Signing and Verifying](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.4.2. Encrypting and Decrypting](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.4.3. Combined Operations](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.4.4. PKCS#7 Flags](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
    1. [10.5. PKCS#12](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.5.1. Wrapping Information into a PKCS#12 Object](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
        1. [10.5.2. Importing Objects from PKCS#12 Data](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_15.html#openssl-CHP-10-SECT)
1. [A. Command-Line Reference](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_16.html)
    1. [asn1parse](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_17.html)
    1. [ca](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_18.html)
    1. [ciphers](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_19.html)
    1. [crl](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_20.html)
    1. [crl2pkcs7](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_21.html)
    1. [dgst](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_22.html)
    1. [dhparam](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_23.html)
    1. [dsa](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_24.html)
    1. [dsaparam](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_25.html)
    1. [enc](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_26.html)
    1. [errstr](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_27.html)
    1. [gendsa](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_28.html)
    1. [genrsa](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_29.html)
    1. [nseq](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_30.html)
    1. [passwd](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_31.html)
    1. [pkcs7](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_32.html)
    1. [pkcs8](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_33.html)
    1. [pkcs12](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_34.html)
    1. [rand](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_35.html)
    1. [req](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_36.html)
    1. [rsa](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_37.html)
    1. [rsautl](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_38.html)
    1. [s_client](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_39.html)
    1. [s_server](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_40.html)
    1. [s_time](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_41.html)
    1. [sess_id](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_42.html)
    1. [smime](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_43.html)
    1. [speed](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_44.html)
    1. [spkac](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_45.html)
    1. [verify](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_46.html)
    1. [version](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_47.html)
    1. [x509](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_48.html)
1. [Index](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_49.html)
1. [About the Authors](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_50.html)
1. [Colophon](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_51.html)
1. [Copyright](https://ebookreading.net/view/book/Network+Security+with+OpenSSL-EB059600270X_52.html)
