# 🔐 JPKI Certificates
These certificates are signed by J-LIS: Japan Agency for Local Authority Information Systems, via JPKI: Japan Public Key Infrastructure.

## 🗂 Files
- **auth.crt.der**: Certificate for user authentication, DER encoded
- **auth.crt.pem**: Certificate for user authentication, PEM encoded
- **sign.crt.der**: Certificate for digital signature, DER encoded
- **sign.crt.pem**: Certificate for digital signature, PEM encoded
- **ca/**:
  - **auth-ca.crt.der**: CA Certificate for user authentication, DER encoded
  - **auth-ca.crt.pem**: CA Certificate for user authentication, PEM encoded
  - **sign-ca.crt.der**: CA Certificate for digital signature, DER encoded
  - **sign-ca.crt.pem**: CA Certificate for digital signature, PEM encoded

## 🔑 Fingerprints
### for User Authentication
- SHA-256: `81 DE D7 D7 B2 65 E8 BB FC 4A 50 96 C9 65 86 39 3C 71 25 15 1D 60 5A 5B 69 47 B8 50 0C 29 AE BC`
- SHA-1: `BC 4B 80 F3 11 C1 F5 E3 58 B9 2F 86 F9 13 C4 36 06 BA 22 CF`

### for Digital Signature
- SHA-256: `A4 16 76 2C 85 BC 71 CA 27 98 60 48 29 30 08 89 49 E2 05 36 9C A1 2D BA CA B3 49 DE 6E 45 A2 52`
- SHA-1: `C1 CA 80 19 4C A2 29 EF 0E F7 75 D4 B8 6E DF C9 B0 A7 5D 42`

## 🔗 References
- 署名用認証局の運営に関する情報
  https://www.jpki.go.jp/ca/ca_rules3.html

- 利用者証明用認証局の運営に関する情報
  https://www.jpki.go.jp/ca/ca_rules4.html
