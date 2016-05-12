# Troubleshooting DOI Resolutions

The CrossRef Export/Registration plugin will notify you of any configuration errors when attempting to deposit DOIs. The errors should be self-explanatory, and will usually indicate whether a configuration step has been missed; whether your CrossRef credentials are incorrect; or whether the service is for some reason unavailable.

NOTE that a status indication of "submitted" or "complete" does not necessarily indicate that a DOI has been successfully registered and is now available via CrossRef - these statuses simply refer to the state of the DOI within the CrossRef workflow. For complete status information, click on the status text.

Most deposit errors will come down to elements missing or misconfigured in your deposit XML. If you are seeing any XML validation errors when checking the status of a deposit, see if you can track the error back to eg. a missing component in your journal or plugin configurations, for example a missing ISSN.
