# SSOT_Pipeline

Présentation d'un pipeline convertissant une documentation procédurale en markdown vers plusieurs type documentaires à l'aide de pandoc.

Les documents obtenus (docx, pdf, ...) sont générés automatiquement par un gitlab CI.

---

Desactivation de la verification TSL/SSL sous git:
`git config --global http.sslVerify false`

Add the content of your self signed certificate to the end of the ca-bundle file. Including the -----BEGIN CERTIFICATE----- and -----END CERTIFICATE----- lines

The location of the ca-bundle file is usually C:\Program Files\Git\mingw64\ssl\certs
    
    Import the Git server self signed certificate into Fisheye/Crucible server according to PKIX Path Building Failed - Cannot Set Up Trusted Applications To SSL Services

    Configure the Git client in Fisheye/Crucible server to refer to the cacerts that have the imported certificate:

    git config --system http.sslCAPath /path/to/cacerts

    Restart Fisheye/Crucible server

test1
test2
test3
test4
test5
test6
test7
test8
test19
