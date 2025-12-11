# Issue Tracker

Thank you for using RMQ! This repository is dedicated to tracking bugs, feature requests, and other issues reported by users.

## Before Submitting an Issue

Please check if your issue has already been reported by searching through existing issues. If you find a similar issue, feel free to add any additional information as a comment.

## How to Submit an Issue

Click the "Issues" tab above and then click "New Issue" to get started.

## What to Include

### For Bug Reports

Please provide the following information to help us diagnose and fix the problem:

**Required Information:**
- **macOS Version**: Which version of macOS are you running? (e.g., macOS 26.1 Tahoe)
- **App Version**: Which version of the app are you using? (Found in the About section or app menu)
- **Description**: A clear description of what went wrong
- **Steps to Reproduce**: Detailed steps to reproduce the issue
  1. Go to '...'
  2. Click on '...'
  3. See error

**Helpful Additional Information:**
- **Expected Behavior**: What you expected to happen
- **Actual Behavior**: What actually happened
- **Screenshots**: If applicable, add screenshots to help explain the problem
- **Connection Details**: Are you connecting via SSH tunnel? Using SSL/TLS? (Don't include credentials)
- **RabbitMQ Version**: What version of RabbitMQ server are you connecting to?
- **Console Logs**: Any error messages from the macOS Console app (if available)

**Example Bug Report:**
```
**macOS Version**: macOS 26.1 Tahoe
**App Version**: 1.0.2
**Description**: App crashes when trying to view bindings for an exchange with no bindings

**Steps to Reproduce**:
1. Open connection to RabbitMQ server
2. Navigate to Exchanges tab
3. Click on an exchange with 0 bindings
4. Click "View Details"
5. App crashes

**Expected**: Should show "No bindings" message
**Actual**: App crashes immediately

[Screenshot attached]
```

### For Feature Requests

Help us understand what you'd like to see added:

**Required Information:**
- **Feature Description**: What feature would you like to see?
- **Use Case**: Why would this feature be useful? What problem does it solve?
- **Suggested Implementation**: (Optional) How do you envision this working?

**Example Feature Request:**
```
**Feature**: Bulk queue deletion

**Use Case**: When cleaning up test environments, I often need to delete dozens of queues at once. Currently I have to delete them one by one which is very time-consuming.

**Suggested Implementation**: Add a checkbox next to each queue in the list view, with a "Delete Selected" button that appears when one or more queues are selected. Include a confirmation dialog showing how many queues will be deleted.
```

### For Questions or Support

If you're not sure if something is a bug or you need help using a feature:

- **Question**: Clearly state what you're trying to do
- **What You've Tried**: Let us know what you've already attempted
- **Context**: Any relevant details about your setup

## What Happens Next?

- Your issue will be reviewed by the development team
- We may ask follow-up questions to better understand the issue
- You'll receive updates as we work on addressing your report
- Closed issues remain visible for reference

## Privacy & Security

**Important**: Please do not include:
- Passwords or credentials
- Private keys
- Sensitive connection information (sanitize hostnames/IPs if needed)
- Proprietary or confidential data

## Contributing

While this repository is primarily for issue tracking, we welcome:
- Detailed bug reports
- Well-explained feature requests
- Constructive feedback on existing features
- Clarifications or additional context on existing issues
- Hilariously worded insults

Thanks for all of the help in making RMQ amazing.

