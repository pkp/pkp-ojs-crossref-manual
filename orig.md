Project Contacts
----------------

-   PKP: [James MacGregor](mailto:pkp.contact@gmail.com)

Project Information
-------------------

PKP and CrossRef are collaborating to help publishers and journals using Open Journal Systems (OJS) take better advantage of CrossRef services. As of 2014, PKP has become a Sponsoring Entity of CrossRef, and as such will be providing much improved CrossRef integration and overall support for the service. Additionally, PKP can now act as a sponsor representative for OJS journals wishing to apply for CrossRef membership, and is in some cases able to waive fees.

DOI and Associated Metadata Export
----------------------------------

PKP is working with CrossRef to improve the level of overall DOI export support provided within OJS. OJS has included a basic manual export plugin for several years; this plugin will be extended in the following ways, and will be freely available to any journal using OJS (2.4.5+).

- automatic DOI deposit to CrossRef on article publication (2.4.5); – inclusion of other article metadata in the CrossRef deposit, including author ORCID iDs; article abstracts; and more (OJS 2.4.5); – inclusion of FundRef funding data (forthcoming); – support for the CrossMark publication record service (forthcoming); – and more.

PKP as Sponsoring Entity
------------------------

As a CrossRef Sponsoring Entity, PKP can also act as sponsor and representative for other journals to join CrossRef through PKP. Journals from low-income countries may be eligible for sponsorship, allowing these journals to become CrossRef members and deposit DOIs into the CrossRef system at no cost.

### Eligible countries

Organizations from the following countries (who are in the [Low Income Country](http://data.worldbank.org/income-level/LIC) category, or in the [Low & Middle Income country list](http://data.worldbank.org/income-level/LMC) and whose GNI per capita is up to \$1,500) may be eligible for sponsorship.


  | Afghanistan (LIC) | Central African Republic (LIC) | Gambia (LIC) | Liberia (LIC) | Niger (LIC) |
  | ----- | ----- | ----- | ----- | ----- |
  | Sudan (LMC) | Bangladesh (LIC) | Chad (LIC) | Guinea (LIC) | Madagascar (LIC) |
  | Pakistan (LMC) | Tajikistan (LIC) | Benin (LIC) | Comoros (LIC) | Guinea-Bassau (LIC) |
  | Malawi (LIC) | Rwanda (LIC) | Tanzania (LIC) | Benin (LIC) | Congo, Democratic Republic (LIC) |
  | Haiti (LIC) | Mali (LIC) | Sao Tome and Principe (LMC) | Togo (LIC) | Burkina Faso (LIC) |
  | Cote d’Ivoire (LMC) | Kenya (LIC) | Mauritania (LMC) | Senegal (LMC) | Uganda (LIC) |
  | Burundi (LIC) | Djibouti (LMC) | Korea, Democratic Republic (LIC) | Mozambique (LIC) | Sierra Leone (LIC) |
  | Yemen Republic (LMC) | Cambodia (LIC) | Eritrea (LIC) | Kyrgyz Republic (LMC) | Myanmar (LIC) |
  | Somalia (LIC) | Zambia (LMC) | Cameroon (LMC) | Ethiopia (LIC) | LAO PDR (LMC) |
  | Nepal (LIC) | South Sudan (LMC) | Zimbabwe (LIC) | | |

For further eligibility criteria and any other information, contact us.

PKP Publishing Services clients
-------------------------------

PKP Publishing Services provides additional CrossRef support. All hosted clients can rely on our internal expertise to assist with plugin setup and support. Additionally, Enterprise clients will now have CrossRef represented membership and DOI deposits included as part of the Enterprise hosting package. For more information, please contact us.

CrossRef Export/Registration Plugin (OJS 2.4.5+)
------------------------------------------------

The CrossRef Export/Registration Plugin can deposit DOIs to the CrossRef database for consideration and acceptance. This can be accomplished in an entirely automatic fashion; manually through OJS; or completely externally to OJS if need be.

### How to Configure OJS for Automatic Deposits

​1. Ensure that all Journal Setup steps that the CrossRef plugin requires have been filled in. Under **Journal Setup Step 1**, you will need the following:

-   Journal Title
-   Journal Initials
-   Journal Abbreviation
-   Journal ISSN (or electronic ISSN)
-   Principal Contact (name and email)
-   Technical Support Contact (name and email)
-   Publisher (Institution and URL)

​2. Enable and configure the "DOI" public identifier plugin at **System Plugins -\> Public Identifier Plugins -\> DOI Plugin**.

-   First, **Enable** the plugin; then configure the plugin **Settings**.
-   For plugin settings, ensure that you have only Articles and Supplementary Files checked for depositing Journal Content.
-   You must also include a DOI prefix which you get from CrossRef, and additionally must configure the DOI suffix. We **strongly recommend** using the default patterns if you are a new journal and have not previously had DOIs issued.

​3. Ensure that your articles have DOIs assigned to them.

​4. Configure the CrossRef Deposit Plugin. This can be done from **Import/Export -\> CrossRef Export/Registration Plugin**.

-   The plugin will tell you whether the overall system requirements have been satisfied.
-   Depositor name and email will be initially retrieved from the journal's Primary Contact information, but you can change this if you like.
-   If you have your CrossRef login credentials, you can supply them here and enable automatic DOI deposit.

### Depositing DOIs with CrossRef

If you have configured the plugin to work automatically, OJS will deposit DOIs as they are created without your intervention. You can check the **Unregistered Articles** page to confirm that DOIs have been deposited.

If you have not configured the plugin to deposit DOIs automatically, you can still register them manually yourself by using the "Register" button on the **Unregistered Articles** or **All Articles** page. Additionally, you can also **Export** the article or issue XML and deposit that to the CrossRef website yourself.

### Troubleshooting

The CrossRef Export/Registration plugin will notify you of any configuration errors when attempting to deposit DOIs. The errors should be self-explanatory, and will usually indicate whether a configuration step has been missed; whether your CrossRef credentials are incorrect; or whether the service is for some reason unavailable.

NOTE that a status indication of "submitted" or "complete" does not necessarily indicate that a DOI has been successfully registered and is now available via CrossRef - these statuses simply refer to the state of the DOI within the CrossRef workflow. For complete status information, click on the status text.

Most deposit errors will come down to elements missing or misconfigured in your deposit XML. If you are seeing any XML validation errors when checking the status of a deposit, see if you can track the error back to eg. a missing component in your journal or plugin configurations, for example a missing ISSN.

### Future Plans

The CrossRef Export/Registration plugin is still undergoing active development. We intend to focus on the following enhancements from OJS 2.4.5 onward.

-   UI/UX review of both the Public Identifier Plugin and the CrossRef Export/Registration Plugin;
-   Add the option to check current DOI status (rather than simply the deposit status), for example whether DOIs are currently "live";
-   Extend the CrossRef deposit XML to include abstracts; reference lists; and more;
-   FundRef; CrossMark additions

