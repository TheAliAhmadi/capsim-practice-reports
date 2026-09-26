# Practice Round Recap

**Live site:** https://thealiahmadi.github.io/capsim-practice-reports/

Flow:
1. Choose section
2. Unlock with student number (OrgDefinedId)
3. Open or download **only that student’s team report**

`unlock.json` stores salted SHA-256 hashes mapped to one report path each (no names/emails). Soft gate on a public static site — direct GitHub file URLs can still bypass the page UI.
