---
title: "Troubleshooting and Solutions"
description: "Common issues and solutions for Brc Pleo"
weight: 20
---

# Troubleshooting and Solutions

This section provides solutions to common issues and troubleshooting guidance for Brc Pleo.

## Common Issues

### Installation Problems

**Issue: Extension installation fails**
- **Cause:** Insufficient permissions or conflicts with existing extensions
- **Solution:** 
  1. Verify you have System Administrator permissions
  2. Check for conflicting extensions in Extension Management
  3. Review the [Setup Guide](../setup/) for prerequisites

**Issue: Extension not visible after installation**
- **Cause:** Extension may not be assigned to current user or company
- **Solution:**
  1. Go to **Extension Management**
  2. Verify Brc Pleo is listed and "Published"
  3. Check user permissions and company assignment

### Configuration Issues

**Issue: Setup page cannot be found**
- **Cause:** Search permissions or extension not properly installed
- **Solution:**
  1. Use **Tell Me** to search for "Brc Pleo"
  2. Verify extension installation status
  3. Check user role permissions

**Issue: Configuration settings not saving**
- **Cause:** Database permissions or field validation errors
- **Solution:**
  1. Verify write permissions to the database
  2. Check required field validation
  3. Review error messages for specific issues

### Runtime Problems

**Issue: Features not working as expected**
- **Cause:** Incomplete configuration or data issues
- **Solution:**
  1. Review configuration settings
  2. Check data integrity and required setup
  3. Verify user permissions for specific features

**Issue: Performance issues**
- **Cause:** Large data volumes or inefficient queries
- **Solution:**
  1. Review data filters and date ranges
  2. Consider archiving old data
  3. Contact support for performance optimization

## Error Messages

### Common Error Codes

*Product-specific error codes and solutions will be documented here as they are identified.*

### General Error Resolution

1. **Record exact error message** - Screenshot or copy the full error text
2. **Note the context** - What action were you performing when the error occurred?
3. **Check recent changes** - Any recent configuration or data changes?
4. **Review prerequisites** - Ensure all setup requirements are met

## Getting Additional Help

### Before Contacting Support

Please gather the following information:

- **Product Version:** Current version of Brc Pleo
- **Business Central Version:** Your BC version and build number
- **Error Details:** Complete error messages and screenshots
- **Steps to Reproduce:** Detailed steps that cause the issue
- **Recent Changes:** Any recent system or configuration changes

### Support Channels

- **Documentation:** Check the [Setup Guide](../setup/) for additional information
- **Support Portal:** [BrightCom Support Portal](https://support.brightcom.se)
- **Email Support:** support@brightcom.se
- **Phone Support:** Available during business hours (CET)

### Business Central Resources

- [Microsoft Business Central Documentation](https://docs.microsoft.com/dynamics365/business-central/)
- [Business Central Community](https://community.dynamics.com/business/)
- [Business Central Learning Center](https://docs.microsoft.com/learn/dynamics365/business-central)

## Diagnostic Information

### System Information to Collect

When reporting issues, include:

1. **Extension Information:**
   - Extension name and version
   - Installation date
   - Company database affected

2. **Environment Details:**
   - Business Central version and build
   - Browser type and version (for web client)
   - Operating system information

3. **User Context:**
   - User permissions and roles
   - Current company and tenant
   - Language and region settings

---

*Last updated: August 2025*

*For immediate assistance with critical issues, contact BrightCom Support at support@brightcom.se*
