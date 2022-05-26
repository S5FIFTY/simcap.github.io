<?xml version="1.0"?>
<EntityDescriptor xmlns="urn:oasis:names:tc:SAML:2.0:metadata" entityID="https://app.onelogin.com/saml/metadata/70f84e24-3710-4991-869d-4e49b87d3a9e">
  <IDPSSODescriptor xmlns:ds="http://www.w3.org/2000/09/xmldsig#" protocolSupportEnumeration="urn:oasis:names:tc:SAML:2.0:protocol">
    <KeyDescriptor use="signing">
      <ds:KeyInfo xmlns:ds="http://www.w3.org/2000/09/xmldsig#">
        <ds:X509Data>
          <ds:X509Certificate>MIIEIzCCAwugAwIBAgIUY0KmxI+i97bzve8ZHlxJY0qye3YwDQYJKoZIhvcNAQEF
BQAwXDELMAkGA1UEBhMCVVMxFDASBgNVBAoMC0xlZSBDb2xsZWdlMRUwEwYDVQQL
DAxPbmVMb2dpbiBJZFAxIDAeBgNVBAMMF09uZUxvZ2luIEFjY291bnQgMTgxNTQ0
MB4XDTIxMDYwODIwMTU0NFoXDTI2MDYwODIwMTU0NFowXDELMAkGA1UEBhMCVVMx
FDASBgNVBAoMC0xlZSBDb2xsZWdlMRUwEwYDVQQLDAxPbmVMb2dpbiBJZFAxIDAe
BgNVBAMMF09uZUxvZ2luIEFjY291bnQgMTgxNTQ0MIIBIjANBgkqhkiG9w0BAQEF
AAOCAQ8AMIIBCgKCAQEAyczM+ptSr9c8ZMx3sEG5VpNWrTVfynxzeo6SccJFGRUt
zZRMJ+mnOUd4MtqDz94yZ/5aGOhXPJ9g9xXdnthAzZquPSBPtU7cWwuOtvWOKuWZ
h6NKKxaahKT04UnBxeiMIt49QDnqUFm3jExGs6bAa2ipcEAaqQDVZQ2zUaiBI0ip
gXH5EeNNxAsdLfAcplmTPYITFbXgog7oOEj49GlmHBxtTMijp+E0VFR2/2ZBwg5g
ke+az/7e1gKp7YCuA+YMvdk74zp1yc8+dFqWIf+nkm1mfM0JoO36JhZ/s9W9TrJo
rSeuACj7Mlf3LSItkgGKl+a5KazRqmuDSnX+uy/a7QIDAQABo4HcMIHZMAwGA1Ud
EwEB/wQCMAAwHQYDVR0OBBYEFG4Gv5XAOKHcC8ulSzL3LFBbPUxfMIGZBgNVHSME
gZEwgY6AFG4Gv5XAOKHcC8ulSzL3LFBbPUxfoWCkXjBcMQswCQYDVQQGEwJVUzEU
MBIGA1UECgwLTGVlIENvbGxlZ2UxFTATBgNVBAsMDE9uZUxvZ2luIElkUDEgMB4G
A1UEAwwXT25lTG9naW4gQWNjb3VudCAxODE1NDSCFGNCpsSPove2873vGR5cSWNK
snt2MA4GA1UdDwEB/wQEAwIHgDANBgkqhkiG9w0BAQUFAAOCAQEAVLqO+k46b24y
YRQ+lPLn8LM4WLhhpHlnsM9hRR9T97aRawSdFmzZ0PeYEpgYzq6OynCSALv5sFa6
n/0MqYv4MX2fmah2tlp37oiI5EQoA2cEAzWIsuG131D7ZxG05VC/9t01QEiZb8CC
WkGSghF78ndE9I6RhQRciisx5OpZ6q8BbMxXeKz05NzDuUMbG83SjEm8X4NWUP7q
YfhVzXxcWvWnpBRlfPAizo0Ia3CvwsCbJufU7RzCw+m0sM7iySWK73v+uVsbW9gG
eCpMPIDXMbx/PQQ/ONC7049HHAakKPEmYs0NErktiKNgTvxsoRWHG8VwOZJtUXQE
neHWzj11oA==</ds:X509Certificate>
        </ds:X509Data>
      </ds:KeyInfo>
    </KeyDescriptor>
    <SingleLogoutService Binding="urn:oasis:names:tc:SAML:2.0:bindings:HTTP-Redirect" Location="https://leecollege.onelogin.com/trust/saml2/http-redirect/slo/1755697"/>
    
      <NameIDFormat>urn:oasis:names:tc:SAML:2.0:nameid-format:persistent</NameIDFormat>
    
    <SingleSignOnService Binding="urn:oasis:names:tc:SAML:2.0:bindings:HTTP-Redirect" Location="https://leecollege.onelogin.com/trust/saml2/http-redirect/sso/70f84e24-3710-4991-869d-4e49b87d3a9e"/>
    <SingleSignOnService Binding="urn:oasis:names:tc:SAML:2.0:bindings:HTTP-POST" Location="https://leecollege.onelogin.com/trust/saml2/http-post/sso/70f84e24-3710-4991-869d-4e49b87d3a9e"/>
    <SingleSignOnService Binding="urn:oasis:names:tc:SAML:2.0:bindings:SOAP" Location="https://leecollege.onelogin.com/trust/saml2/soap/sso/70f84e24-3710-4991-869d-4e49b87d3a9e"/>
  </IDPSSODescriptor>
</EntityDescriptor>
