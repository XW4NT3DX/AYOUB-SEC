
...

### A06: Vulnerable and Outdated Components

Modern applications are built using a large number of third-party libraries (which themselves are dependent on other libraries), and frequently run on open-source frameworks. In a modern application there may be orders of magnitude more code from libraries and components than written by an organization’s developers.

As might be expected with any software, vulnerabilities in libraries and components will routinely be discovered, patched, and new versions released. The challenges of identifying all the components in use, keeping track of their vulnerability status, and routinely rebuilding and testing deployed software is both essential and onerous. Perhaps this is why so many organizations are still running vulnerable software in production.

A critical mitigation step is to build a Software Bill of Materials (SBoM) for all the software deployed or supplied to customers. Veracode Software Composition analysis and Container Scanning tools can produce SBoMs in standardized formats to give organizations a view of their exposure to vulnerabilities in third-party components.

### A07 Identification and Authentication Failures
Identifying and authorizing users and non-human clients is a fundamental security practice. It goes without saying that weaknesses in a way an application allows access or identifies users is a critical vulnerability.
While mitigation starts with secure coding practices, tools to detect and prevent credential stuffing and brute force attacks are also useful protections.

### A08: Software and Data Integrity Failures
The tools used to build, manage, or deploy software are increasingly common vectors of attack. A CI’CD pipeline that routinely builds, tests and deploys software can also be used to inject malicious code (or libraires), create insecure deployments, or steal secrets.

As discussed above in ‘Vulnerable and Outdated Components’ modern applications use many third-party components, often pulling them from third party repositories.

Organizations can mitigate this threat by ensuring both the security of the build process, and the components pulled into the build. Adding in code scanning and software component analysis steps into a software build pipeline can identify malicious code or libraries.

### A09: Security Logging and Monitoring Failures
Having adequate logging and monitoring in place is essential in both detecting a breach early, hopefully limiting the damage, and in incident forensics to establish the scope of the breach, and to determine the method of compromise.

Simply generating the data is obviously insufficient, organizations must have adequate collection, storage, alerting and escalation processes. Organizations should also verify that these processes are working correctly – using Dynamic Application Security Testing (DAST) tools like Veracode DAST, for instance, should produce significant logging and alerting events.
### A10: Server-Side Request Forgery (SSRF)

Modern web applications commonly fetch additional content or data from a remote resource. If an attacker can influence the destination resource, and the application does not validate the supplied URL, then a crafted request may be sent to a target destination.

Mitigating SSRF attacks is done using familiar methods such as sanitizing user input, using explicit allow lists, and inspecting request responses before they are returned to clients.