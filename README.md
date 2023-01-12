# Security

## LDAP
LDAP (Lightweight Directory Access Protocol) is an open, vendor-neutral, industry standard application protocol for accessing and maintaining distributed directory information services over an Internet Protocol (IP) network. 
LDAP is commonly used to store and manage user authentication and authorization information(passwords and group memberships) and other types of data (configuration settings, application-specific data ...).

## OpenLDAP
OpenLDAP is an open-source implementation of the Lightweight Directory Access Protocol (LDAP). It stores data in a hierarchical structure called a directory tree, with a single root node called the "Directory Information Tree (DIT)". Each node in the tree is called an "entry" and contains a set of attributes, such as name, email, and telephone number... Entries are organized in a logical way, similar to a file system directory structure, allowing for easy navigation and searching of the data.

## TLS
TLS (Transport Layer Security) is a widely-used security protocol that is designed to provide secure communications over the internet.
TLS works by creating a secure, encrypted channel between two devices. This channel is used to transmit sensitive information, such as login credentials, credit card numbers, and other personal data, so that it cannot be intercepted and read by unauthorized parties.
TLS uses a combination of public key and symmetric key encryption to secure the connection. 
1. The client and server agree on a set of security parameters, such as the encryption algorithm and key size to use. 
2. The client authenticates the server's identity by checking its digital certificate, which is issued by a trusted certificate authority (CA). 
3. Once the server's identity has been verified, the client and server exchange a series of keys to establish a secure connection. 

## PKI
PKI (Public Key Infrastructure) is a set of hardware, software, policies, and procedures that are used to create, manage, and distribute digital certificates. Digital certificates are used to establish trust in online transactions and to secure communication over networks.
PKI uses a pair of keys, one public and one private, for an asymmetric encryption . The public key is used to encrypt data that is sent to the owner of the private key, and the private key is used to decrypt the data.
A PKI system  includes :
1. Certification Authority (CA): the organization that issues and manages digital certificates: verify the identity of certificate applicants and revoke certificates that are no longer valid.
2. Digital Certificates: electronic documents, issued by the CA,  that bind a public key to an identity. They contain information such as the certificate holder's name, public key, and a digital signature from the CA.
3. Certificate Revocation List (CRL): a list of revoked certificates that is published by the CA, used to check the validity of a certificate before it is used.
4. Registration Authority (RA): This is an entity that acts as an intermediary between the certificate holder and the CA. It is responsible for verifying the identity of certificate applicants and for forwarding the certificate request to the CA.
5. Public Key Infrastructure X.509 (PKIX): a set of standards that are used to implement PKI. They include the X.509 certificate standard, which defines the format of digital certificates, and the Internet Public Key Infrastructure (PKI) Certificate Management Protocol (CMP), which is used to manage digital certificates.
