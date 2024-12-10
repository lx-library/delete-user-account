# LX Library Account Deletion Interface

This repository contains the web interface for secure and streamlined account deletion for LX Library users.

## Overview

The account deletion page provides a user-friendly, secure mechanism for users to request permanent account removal, with built-in safeguards and direct API integration.

## Key Features

- Secure account deletion request submission
- Real-time API integration with LX Library backend
- Comprehensive user confirmation process
- Responsive web design
- Clear warning about account deletion consequences

## Repository Structure

```
├── index.html        # Main account deletion interface
├── assets/
│   └── logo.png      # Company logo
└── README.md         # Project documentation
```

## Implementation Details

- Vanilla JavaScript for frontend logic
- Fetch API for secure request submission
- Built-in client-side validation
- Informative warning notices
- Mandatory user confirmation checkbox

## User Experience Flow

1. User enters account credentials
2. Provides reason for account deletion
3. Confirms understanding of irreversible action
4. Submits request via secure API endpoint
5. Receives confirmation toast notification
6. Expects follow-up communication via email

## Deployment Considerations

- Requires HTTPS for secure form submission
- Depends on `lxlibrary.online/v2/api/admin/tasks` endpoint
- Recommended to implement additional server-side validation

## Requirements

- Modern web browser
- JavaScript enabled
- Active internet connection

## Version History

- v1.0.0 - Initial account deletion interface release

## Security Notes

- Sensitive information is transmitted via secure HTTPS
- Minimal client-side data retention
- Direct integration with official LX Library systems

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contact

**LX Library (Pty) Ltd**  
Keagan Gilmore  
Email: keagangilmore@gmail.com  
Tel: +27 83 510 7047

---
© 2024 LX Library (Pty) Ltd. All rights reserved.