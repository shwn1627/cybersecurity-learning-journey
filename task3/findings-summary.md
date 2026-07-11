\# Vulnerability Assessment Findings



\## Target



OWASP Juice Shop (Docker Container)



\---



\## Assessment Tools



\- Nmap

\- Nikto

\- Dirsearch



\---



\# Findings



| Finding | Severity | Tool |

|----------|----------|------|

| Port 3000 Open | Medium | Nmap |

| HTTP Service Accessible | Medium | Nmap |

| Missing Content Security Policy | Medium | Nikto |

| Missing HSTS Header | Medium | Nikto |

| Missing Referrer Policy | Low | Nikto |

| Missing Permissions Policy | Low | Nikto |

| X-Content-Type-Options Missing | Low | Nikto |

| robots.txt Accessible | Low | Nikto |

| API Documentation Exposed | Medium | Dirsearch |

| Swagger Interface Accessible | Medium | Dirsearch |

| Login API Endpoint Found | Low | Dirsearch |

| Version Endpoint Exposed | Low | Dirsearch |



\---



\# Overall Risk



Medium



\---



\# Recommendations



\- Implement Content Security Policy.

\- Enable HTTP Strict Transport Security.

\- Restrict unnecessary API documentation.

\- Limit exposure of sensitive endpoints.

\- Regularly perform vulnerability assessments.

\- Keep dependencies updated.



\---



\# Conclusion



The assessment identified several intentionally vulnerable configurations within OWASP Juice Shop. These findings demonstrate common web application security weaknesses and provide practical experience in vulnerability assessment using industry-standard tools.

