# 8.0

- integrate the new Sitecore NuGet feed and reference the relevant NuGet packages from there
- target Sitecore 8.1 update 1 as the minimum supported version (Introduction of the PageMode.IsExperienceEditor flag)
- replace the Sitecore Analytics integration with the new xDB API
- introduce support for basic authentication
- introduce support for forwarding configured headers
- introduce support for excluding specific cookies from forwarding to the error page
- introduce support for disabling the xDB tracker for requests initiated by the error manager
- fix a Sitecore bug with item language fallback introduced with Sitecore 8.1 update 3 