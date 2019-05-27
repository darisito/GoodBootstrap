<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [sendRecoveryInstructionsByEmail][1]
    -   [Parameters][2]
-   [sendEmailConfirmationLink][3]
    -   [Parameters][4]

## sendRecoveryInstructionsByEmail

Sends an email with recovery instructions to the user's registered email through SendGrid.
Send it by an API using a Transactional Template

### Parameters

-   `to` **[string][5]** User email
-   `name` **[string][5]** User name
-   `key` **[string][5]** Mnemonic key

Returns **([Promise][6]&lt;R> | [Promise][6]&lt;(R | any)>)** 

## sendEmailConfirmationLink

Sends an email to the user's registered email through SendGrid.send API using a Transactional Template

### Parameters

-   `user` **UserRecord** User profile

Returns **([Promise][6]&lt;R> | [Promise][6]&lt;(R | any)>)** 

[1]: #sendrecoveryinstructionsbyemail

[2]: #parameters

[3]: #sendemailconfirmationlink

[4]: #parameters-1

[5]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[6]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise
## Source
[https://github.com/GoodDollar/GoodServer/src/server/send/send.sendgrid.js](https://github.com/GoodDollar/GoodServer/src/server/send/send.sendgrid.js)
