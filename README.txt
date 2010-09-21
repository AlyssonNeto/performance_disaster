Before using this module you need to create a lot of users.

Use the devel_generate module to create 50,000 users.

drush genu 50000

Then place the "Random Users" block provided in one of the sidebars.

Enable cron to run every minute so that the caching solution will work.

Enable devel module, enable queries, and sort by duration.

Don't forget to use the Slow Query log to show this also.