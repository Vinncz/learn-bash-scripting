# Cron

## Topics

### Cron Job
A cron job is an automated task that is executed per specification of a `crontabs file`.

Access the `crontabs file` using the `crontab -e` command.

The syntax is as follows:\
`<minute> <hour> <day of month> <month> <date of week> <command>`

Which roughly used like so:\
`30 15 * * 0 date >> log.txt`

That translates to:\
`30 minutes past 3PM, on Sunday of every week of every month, execute "date >> log.txt"`

You can also write:\
`0 0 * * * date >> log.txt`

That translates to:\
`Right on the hour at midnight, everyday of the month, execute "date >> log.txt"`

* If a spot is left empty, it'll be executed on the lowest interval possible.
