# Cron

## Topics

### Cron Job
A cron job is an automated task that is executed per specification of a `crontabs file`.

The syntax that configure when the job is invoked is as follows:\
`<minute> <hour> <day of month> <month> <date of week> <command>`

Which roughly used like so:\
`30 15 * * 0 date >> log.txt`

That translates to:\
`30 minutes past 3PM on Sunday, execute "date >> log.txt"`
