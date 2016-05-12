CrossRef Export/Registration Plugin (OJS 2.4.8+)
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
