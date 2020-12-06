# Ansible SME Linux Environment

A template environment to build a lab where you can:
- Test service misconfigurations
- Test exploits
- Attach vulnerable machines (e.g. from Vulnhub)
- Mimic an assessment environment

## Configuration

Ansible directory structure is according to the [Beste Practices](https://docs.ansible.com/ansible/2.3/playbooks_best_practices.html#directory-layout).
Website for webserver is stored in `www`.
Tests are in `test`


## TODO

- Implement tests:
    - ws
    - router
    - webserv
    - dnsserv
    - dhcpserv
    - sambaserv
    - ldapserv
    - intranetserv
- Implement mail server
- Implement OpenLDAP
- Implement [VyOS OpenSSH](https://docs.vyos.io/en/latest/vpn/openvpn.html#server)
- Implement template setup for pivoting
