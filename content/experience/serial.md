+++
title = "External consultant (software engineer) for SERIAL SA"
project = "The Portfolio management system of the bank had been written in the mid-nineties in `C++` and compiled with a non-ANSI (Sun) compiler. The goal of the project was to port the code to standard `C++ 98`."
date = "2017-03-24T19:28:09-05:00"
end_date = ""
main_achievements = [
  "There was no unit or integration test of the system at all. In order to ensure that the new system behave correctly, I did implement a way to record and replay real-world requests. I use these recordings on the ported code to validate it.",
  "The memory leaks in the code were quite important. Moreover, the code was intensively using shared pointers which didn't help fixing the leaks. In order to spot and fix them, I did use IBM Rational Purify to log the pointer address and the call stack at each increase or decrease of the pointer reference count. Then, with some `python` sorting, I was able to directly spot the place where the decrease reference calls were missing."
]
display_project = true
start_date = "2008"
responsabilities = [
  "`C++` code migration on a **Sun Solaris** system.",
  "Migration of middleware [**Tuxedo**](http://www.oracle.com/technetwork/middleware/tuxedo/overview/index.html) from version 6.5 to 10.",
  "Fixing memory leaks that where handled previously by a reboot mechanism."
]
logo = "serial.png"
company = "Serial SA / Union Banquaire Privée"
website = "https://www.serial.ch"
+++
