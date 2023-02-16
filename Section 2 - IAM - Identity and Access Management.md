# 2\. IAM - Identity and Access Management Section

 

## 14\. IAM Introduction: Users, Groups, Policies

-   It's a Global service.

-   Using IAM you can create users for your organization.

-   It's also possible to make groups to categorize people of a similar field for instance.

-   A user can belong to multiple groups, but a group can't contain other groups.

 

> **IAM: Permissions**

-   Users or Groups can be assigned JSON documents called policies. In other words, this JSON file tells the users/groups what they are allowed to do.

-   In AWS you apply the least privilege policy: don't give more permissions than a user needs.

 
 

## 15\. IAM Users & Groups Hands On

-   Root user credentials

    -   The credentials of the account owner allow full access to all resources in the account. You cannot use IAM policies to explicitly deny the root user access to resources.

    -   There are specific tasks that are restricted to the AWS account root user. For example, only the root user can close your account.

 
 

## 16\. IAM Policies

 

**IAM Policies Inheritance**

-   Attaching a policy to a group level means that everyone in that group will have that policy.

-   Because an user can belong to multiple groups, the policies asigned to all the groups will be assigned to that user as well.

    -   **Inline policy -** It's a policy that's only attached to a user.

 

**IAM Policies Structure**

-   Consists of:

    -   *Version (required):* Policy language version, contains a date.

    -   *Id (optional):* For Identifying the policy.

    -   *Statement (required):* One or more.

        -   *Sid (optional):* For identidying the statement.

        -   *Effect (required):* Whether the statement allows or denies access to specific APIs.

        -   *Principal (optional):* Account/user/role to which this policy applied to.

        -   *Action (required):* List of actions this policy allows or denies.

        -   *Resource (required):* List of resources to which the actions applied to.

        -   *Condition (optional):* Conditions for when the policy is in effect.

 
 

## 17\. IAM Policies Hands On

-   The "\*" symbol means "any".

 
 

## 18\. IAM MFA Overview

**IAM - Password Policy**

-   In AWS, it's possible to setup your own password policy, such as:

    -   Require specific character types.

    -   Set a minimum password length.

-   Allow or not IAM users to change their own passwords.

-   Require users to change passwords after some time.

-   Prevent password re-use.

 

**Multi Factor Authentication - MFA**

-   It's important to protect your Root Accounts and IAM users.

-   Users can have access to your account and modify resources.

-   MFA = password tht you know + security device that you own.

-   Therefore, if another device attempts to access an account it will not go through.

-   **MFA devices options**

    -   Virtual MFA device

        -   Google Authenticator (phone only)

        -   Authy (multi-device) - Allows multiple tokens on a single device.

    -   Universal 2nd Factor (U2F) Security Key

        -   This is a pendriave that allows authentication.

        -   It supports multiple root and IAM users using a single security key.

    -   Hardware Key Fob MFA device

    -   Hardware Key Fob MFA Device for AWS GovCloud (US) - Special Key Fob for US government.