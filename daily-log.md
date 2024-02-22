# Daily Log

## 2024-02-06 Session 1 (1h)

Created repository for this project, named embedded-systems-in-10-000-hours.

## 2024-02-07 Session 1 (1h)

Created document to hold list of abbreviations from the field of embedded systems.

## 2024-02-07 Session 2 (1h)

Created introduction note, explaining what an embedded system is.

## 2024-02-08 Session 1 (1h)

Bought the book Intermediate C Programming in E-book format. Turned out that required an special app to read, called Bookshelf, so had to install this as well.

Created a new note called c-programming.md to collect material related to the C programming language.

## 2024-02-08 Session 2 (1h)

Read up on C Programming in the book Intermediate C-Programming [(Lu, 2024)](references.md/#lu-2024), took notes in c-programming.md.

## 2024-02-09 Session 1 (1h)

Read up on tool chains for C-development, especially on text-editors used to write source code, took some notes in c-programming.md.

## 2024-02-09 Session 2 (1h)

Read up on the Linux command `sed` that can be used to automate editing of files. Wrote about `sed` in [linux-commands](linux-commands.md).

## 2024-02-09 Session 3 (1h)

Read up on C programming tool chains and took notes in [c-programming.md](c-programming.md#tool-chains.)

## 2024-02-10 Session 1 (1h)

Worked on improving understanding best practices for running GCC on Windows. Read up on what MSYS2 is and upgraded my MSYS2 installation on my Dell work laptop.

## 2024-02-10 Session 2 (1h)

Playing around with the Linux command `sed` by the use of WSL running under Windows 10.

## 2024-02-11 Session 1 (1h)

Read-up on BLE in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023).

## 2024-02-11 Session 2 (1h)

Continued reading up on BLE in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023).

## 2024-02-12 Session 1 (2h)

Continued reading up on BLE in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Also downloaded and had a brief look at The Bluetooth Low Energy Primer [(Bluetooth SIG, 2023)](references.md#bluetooth-sig-2023).

## 2024-02-13 Session 1 (1h)

Learned and took notes on BLE device addresses based on information from the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023).

## 2024-02-14 Session 1 (1h)

Learned and took notes on BLE packet formats based on information from the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023).

## 2024-02-15 Session 1 (2h)

Read up on details on BLE advertising in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Then also looked into use cases for BLE technology and took some notes on this topic.

## 2024-02-16 Session 1 (1h)

Read up on on mechanics for BLE connections in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Learned about *connection events* where the peripheral and central exchange packets during a connection, and that there is a pause between connection events known as the *connection interval*.

## 2024-02-17 Session 1 (2h)

Updating GCC through MSYS2 on the home computer. Had issues getting the latest GCC version to become the default. Getting latest GCC and updating the PATH environment variable to point to the MSYS2 folder did not help. What seemed to work in the end was to delete old MINGW folders from some previous installation.

## 2024-02-17 Session 2 (1h)

Worked on my mathematical foundations be reading in the book Numerical Mathematics and Computing, David R. Kincaid, E. Ward Cheney. Learned about Horner's algorithm that can be used to calculate (approximate) values of polynomials as well as taking the derivatives of polynomials.

## 2024-02-18 Session 1 (1h)

Did an exercise from the book Numerical Mathematics and Computing, learned how to calculate absolute errors and relative errors when having an approximation for a value, in this case it was approximations of pi with fractions such as 22/7.

## 2024-02-18 Session 2 (2h)

Bought the book the Creative Programmer and read parts of this. Brand new books, have only a few reviews so far, but seems like a good book. It is about soft skills and is supposed to make you a better problem solver as a programmer. Worth a try to read the book.

## 2024-02-19 Session 1 (1h)

Continued reading of Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Now on the chapter on security and privacy. Information was not very deep. Did learn that it is possible to have different security for individual characteristics and. Can chose to have some  characteristics open for everyone and keep some secret, only available for authenticated connections.

## 2024-02-20 Session 1 (1h)

Continuation of reading in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Did a fast read of the chapter on Bluetooth LE Audio, not something I have need for at the moment so just wanted a quick orientation on this topic. Learned about the BLE state known as *Isochronous Broadcasting* that is is used with Bluetooth LE Audio. Was new to me that there are two streams for headphones, one for left and one for right, and the mechanism for syncing the sound in those two streams. Also learned to identify the now logo for the BLE audio related trademark called AuraCast.

## 2024-02-20 Session 2 (1h)

Read up on Bluetooth Mesh in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). This is a technology that allows for building a *many-to-many* topology of Bluetooth nodes. Can for example be used for setting up a network of light switches and light bulbs, where one switch can control many bulbs, and vice versa.

## 2024-02-21 Session 1 (1h)

Reading in the book The Creative Programmer. The author argues that technical knowledge is a pillar stone for being creative. I agree with this opinion based on that if you do not know what other already have done can we still be creative but with the caveat that we might invent something that already exists, and possibly wasting a lot time during the process. Firs step to gain knowledge is to actually connect to an input source, can be books, courses, blogs, podcasts, videos, and attending presentations. Next step is to make the knowledge internalized, making it stick in the brain. Good ways acheive this is to quiz yourself, taking notes and then especially good if writing about the content in your own words, can also explain the concept to someone else (if finding anyone that will listen, as a fall back explain to your pet or a rubber duck).

## 2024-02-21 Session 2 (1h)

Finished the chapter on Bluetooth Mesh in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Learned that using Bluetooth Mesh enables usage of a standardized capability for firmware updates. This is great news because in all the projects I have been involved in we have had to implement firmware upgrade support from scratch which is time consuming.

## 2024-02-22 Session 1 (1h)

Read the chapter on Bluetooth Beacons in the book Intro to Bluetooth Low Energy [(Afaneh, 2023)](references.md#afaneh-2023). Already familiar with the Beacon concept, chapter was hence mostly a refresher. Learned about the existence of the [Android Beacon Library](https://altbeacon.github.io/android-beacon-library/) that can be used for beacons handling in Android.
