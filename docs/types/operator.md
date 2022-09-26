<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

*   [Operator][1]
*   [AuthoriseOperatorResponse][2]
    *   [Properties][3]
*   [AuthorisedOperatorsAccount][4]
    *   [Properties][5]
*   [AuthorisedOperatorsAccountResponse][6]
    *   [Properties][7]
*   [CheckOperatorRolesResponse][8]
    *   [Properties][9]

## Operator

## AuthoriseOperatorResponse

Type: {tnxId: [string][10], authorisedOperatorsPk: PublicKey, operatorPk: PublicKey}

### Properties

*   `tnxId` **[string][10]**&#x20;
*   `authorisedOperatorsPk` **PublicKey**&#x20;
*   `operatorPk` **PublicKey**&#x20;

## AuthorisedOperatorsAccount

Type: {authority: PublicKey, operatorList: [Array][11]\<PublicKey>}

### Properties

*   `authority` **PublicKey**&#x20;
*   `operatorList` **[Array][11]\<PublicKey>**&#x20;

## AuthorisedOperatorsAccountResponse

Type: {publicKey: PublicKey, operatorsAccount: [AuthorisedOperatorsAccount][4]}

### Properties

*   `publicKey` **PublicKey**&#x20;
*   `operatorsAccount` **[AuthorisedOperatorsAccount][4]**&#x20;

## CheckOperatorRolesResponse

Type: {operatorPk: PublicKey, admin: [boolean][12], market: [boolean][12], crank: [boolean][12]}

### Properties

*   `operatorPk` **PublicKey**&#x20;
*   `admin` **[boolean][12]**&#x20;
*   `market` **[boolean][12]**&#x20;
*   `crank` **[boolean][12]**&#x20;

[1]: #operator

[2]: #authoriseoperatorresponse

[3]: #properties

[4]: #authorisedoperatorsaccount

[5]: #properties-1

[6]: #authorisedoperatorsaccountresponse

[7]: #properties-2

[8]: #checkoperatorrolesresponse

[9]: #properties-3

[10]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String

[11]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Array

[12]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean