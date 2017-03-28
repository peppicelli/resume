+++
title = "External consultant (software engineer) for SERIAL SA"
project = "The Portfolio management system of the bank has been written in the mid-nineties in C++ and compiled with a non-ANSI (Sun) compiler. The goal of the project was to port the code to standard C++98."
date = "2017-03-24T19:28:09-05:00"
end_date = ""
main_achievements = [
  "There were no unit or integration test of the system at all. In order to ensure that the new system behave correctly, I did implement a way to record and replay real world requests. I use these recording on the ported code in order to validate it.",
  "The code was using a ton of shared pointers. In order to spot and fix the leak, I did use IBM Rational Purify to log the address and the call stack at each increase or decrease of the pointer reference count. Then, with some python sorting, I was able to produce directly spot the decrease reference calls that were missing."
]
display_project = true
start_date = "2008"
responsabilities = [
  "`C++` code migration on a **Sun Solaris** system.",
  "Migration of middleware **Tuxedo** from version 6.5 to 10.",
  "Fixing memory leaks that where handled previously by a reboot mechanism."
]
logo = "serial.png"
company = "Serial SA / Union Banquaire Privée"
website = "www.serial.ch"
+++
