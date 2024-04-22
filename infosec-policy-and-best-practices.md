# Information Security Policy & Best Practices

## Context

As part of the Good Work team, we handle and have access to information and data that originates from our partners, customers and users. It is important for Good Work to ensure best practices are observed to avoid mishandling of data and information that could result in data loss or compromise. Please read and acknowledge the following document as part of your responsibility as a Good Work employee. 

### Designated work computer

You are required to work on an Apple computer hardware, running the latest macOS version available to your hardware. An exception can be made only upon discussion with your team lead, and with written documentation of the reason behind such an exception. The following protection must be activated on your macOS system: 

- Ensure that a password is always required to log in to your macOS system
- Ensure system screen lock time is set to no shorter than 15 minutes
- Ensure your macOS is always kept up-to-date with the latest security patches via the System menu.
- Ensure that the macOS Firewall is enabled. If the Firewall is temporarily disabled for development purposes (e.g. allowing incoming connections via `ngrok`), you are responsible for ensuring that it is re-enabled once the relevant development task is completed.
- In the event where your work computer needs to be decommissioned, you are required to consult with your team lead to ensure the hardware is securely wiped using [macOS Erase Assistant utility](https://support.apple.com/en-ng/guide/mac-help/mchl7676b710/mac). 

### Data storage and transfer

1. You are only allowed to store and work on work-related data on you *designated work computer*. You are not allowed to make a copy of work data on other computers without prior permission from your team lead.
2. When storing and transferring work data online to coworkers, partners or clients, you are only allowed to upload and facilitate the transfer of such data on the Good Work Workspace Google Drive. This ensures that access to the file is kept secure, backed-up and virus-free.
3. You are *not allowed* to store or transfer data on a physical hard drive or thumb drive, aside from the hard disk of your designated work computer.

### Work email

1. You are required to use your official work email account for all work-related email communication. This will be your `@goodwork.sg` email address provided when your employment starts.
2. When sending file attachments, ensure that you are either uploading the file to Good Work's Google Workspace via Google Drive, or attaching it to your email sent from your @goodwork.sg address directly. This ensures that files are automatically checked for malware before they are sent.

### Database access

1. Provisioning of databases is managed by the tech lead and any team member of the back-end developer role. 
2. As part of your work, you might get access to databases. It is your responsibility to keep database credentials secure, by observing the following best practices:  
  i. Always keep database credentials in a `.env` file, and always add `.env` files (any environment variable file) to the `.gitignore` list so that credentials are never committed to the code repository
  ii. Always look out for GitGuardian alerts in your email, which flags any potential leaks in credentials in Good Work's Git repositories. In the event where a GitGuardian is raised, escalate the incident with your team lead immediately for resolution
3. When handling customer data, including user-generated data and client data, you are required to seek confirmation from your team lead on allowed usage if data needs to be replicated or inserted into any database, including any cloud-hosted database.
4. You are required to seek permission from your team lead before duplicating or transferring production data, or any data that potentially contains customer or user generated data, to your computer for development purposes.

## Evolving document

This document will evolve to address new areas of concern on an ongoing basis. When changes occur, your team lead will onboard you to the relevant changes and this document will serve as the point of reference for applicable best practices and policies. 
