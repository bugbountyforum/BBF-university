# Checklist
This is a basic checklist of vulnerabilities / configurations you can resolve before launching a bug bounty / coordinated vulnerability disclosure program which will lower the amount off reports dramatically.

### DNS records

- [ ] Same site scripting
- [ ] Subdomain take-over
- [ ] SPF / DMARC records
- [ ] X-Frame-Options / clickjacking

### Forms

- [ ] Autocomplete on sensitive forms
- [ ] Rate limiting on sensitive forms

### Authentication

- [ ] Directory Listing
- [ ] Cookies without secure flag (when needed)
- [ ] Authentication over HTTP
- [ ] Failure to Invalidate Session on Logout
- [ ] Failure to Invalidate Session on Password change

### SSL
- [ ] Lack of Forward Secrecy
- [ ] Weak Cipher
- [ ] Poodle Bug
- [ ] Expired SSL Certificate
