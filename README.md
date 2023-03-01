# remind

## Name

`remind` — Desktop notifications and reminders

## Synopsis

	remind help
    remind MESSAGE <in|at> TIME…
    remind <list|clear>

Examples:

    remind "Pasta" in 7 minutes
    remind "Meeting with boss" at 8:55

See `man remind` (or the [source](man/remind.1.ronn)) for the complete manual.

## Dependencies

* `x11-libs/libnotify`
* `sys-process/at`
* `ronn` (for manual)

## References

* [Send desktop notifications and reminders from Linux terminal](https://opensource.com/article/22/1/linux-desktop-notifications) (article by the author)

## Author

Created by Tomasz Waraksa, modified by Roman Lacko.
