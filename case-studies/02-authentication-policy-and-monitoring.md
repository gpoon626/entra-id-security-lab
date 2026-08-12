# Authentication Policy and Monitoring

> Status: Draft

## Overview

This case study documents authentication monitoring and policy testing in a Microsoft Entra ID lab. The work involved generating and investigating a failed authentication event and configuring a Conditional Access policy in report-only mode.

## Activities Completed

* Generated a failed authentication event using a test account.
* Located and reviewed the event in Microsoft Entra sign-in logs.
* Examined the failure code, timestamp, IP address, location, browser, and device information.
* Created a Conditional Access policy requiring multifactor authentication for the test account.
* Configured the policy in report-only mode to evaluate its potential effect without enforcing it.

## Initial Findings

The failed event returned error code `50126`, indicating that the supplied username or password was invalid. Because primary authentication failed, this should not be classified as a failed MFA event.

Location information was treated as supporting context rather than definitive evidence. IP addresses, device details, authentication history, and user behavior must be correlated before determining whether an event is suspicious.

## Security Concepts Demonstrated

* Authentication-log analysis
* Conditional Access
* Multifactor authentication
* Report-only policy testing
* Evidence correlation
* Least-privilege policy deployment

## Evidence

Sanitized screenshots and additional findings will be added after review.
