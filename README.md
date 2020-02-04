# Shiny Auto Refresh

Per [this community
discussion](https://community.rstudio.com/t/auto-refresh-persistently-displayed-shiny-app-when-new-version-is-deployed-to-rstudioconnect/50513?u=cole),
dashboards that are shown / auto-updating on monitors have the occasional need
to refresh automatically. The simplest way to do so is with a timer that
auto-reloads the app every X minutes.

This app shows a simple pattern for how to accomplish using `shinyjs` to embed
a timer into the frontend of the application (using `setTimeout()`).

The JavaScript could easily be added as a `<script>` tag in the HTML, as well.
