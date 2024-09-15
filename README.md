# Email-Domain-Verifier
Purpose:
An email verifier tool validates email addresses to ensure their correctness and existence.
It helps prevent sending emails to invalid or non-existent addresses, reducing bounce rates and improving deliverability.
Features:
Syntax Checking:
Validates email addresses using regex patterns to ensure they follow the correct format.
Mail Server Existence Check:
Verifies the availability of the email address domain by checking DNS records.
SMTP Verification:
Performs an email verification lookup via SMTP (Simple Mail Transfer Protocol).
Detects catch-all email addresses (where all emails to the domain are accepted).
MX (Mail Exchange) Validation:
Checks the DNS MX records for the given domain name.
Miscellaneous Validation:
Detects free email providers (e.g., Gmail, Yahoo).
Identifies role accounts (e.g., admin@domain.com, support@domain.com).
Flags disposable email addresses (DEA).
Usage Example:
You can use the email-verifier Go library to verify email addresses:
