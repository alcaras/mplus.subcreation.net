# mplus.subcreation.net
overview
this website only for education purpose
Source code for a site that used to show statistical analysis of M+ in WoW.

For a simpler version of the same idea, see https://github.com/alcaras/mplus-analysis

This code is what the site is currently running.

It's set up to run as an App Engine instance that runs a cron job that updates data and generates static HTML, writing directly to a Cloud Storage instance. A bit strange, but it scales quite nicely since it only ever serves static HTML pages externally.
