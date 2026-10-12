# Hi, I'm Tony Bringardner 👋

**Retired CTO, lifelong programmer.** Fifty years in information technology: from entry-level
programmer to CTO of a large financial organization, with team lead, project lead and architect
roles in between. I've designed, built and run large systems, but writing code is what I've always
loved most. Now that I'm retired, I do it full time, mostly in Java.

I'm fascinated by network communications and open Internet protocols. I don't think you can really
understand a protocol until you've written both a client and a server for it, so that's what I do.

## What I'm building

### [Parley](https://github.com/tony-bringardner/parley-parent): Java libraries for Internet protocols
Small, dependency-free building blocks for writing both ends of line-based network protocols.

| Protocol | Repo |
|---|---|
| Core (properties, logging, threads, TCP/SSL) | [parley-core](https://github.com/tony-bringardner/parley-core) |
| Line-based client/server framework | [parley-net](https://github.com/tony-bringardner/parley-net) |
| FTP client + server | [parley-ftp](https://github.com/tony-bringardner/parley-ftp) |
| SSH client + server | [parley-ssh](https://github.com/tony-bringardner/parley-ssh) |
| SMTP (with DKIM, SPF, DMARC, ARC) | [parley-smtp](https://github.com/tony-bringardner/parley-smtp) |
| IMAP / POP3 | [parley-imap](https://github.com/tony-bringardner/parley-imap), [parley-pop3](https://github.com/tony-bringardner/parley-pop3) |
| DNS server | [parley-dns](https://github.com/tony-bringardner/parley-dns) |
| A `java.io.File`-like API over local, memory, FTP, SFTP and JDBC | [parley-files](https://github.com/tony-bringardner/parley-files) |

Use [parley-bom](https://github.com/tony-bringardner/parley-bom) to keep the module versions aligned.

### [fsh](https://github.com/tony-bringardner/fsh): a bash-compatible shell written in Java
Runs bash scripts and works interactively, over *any* `FileSource`, so you can `cd` into an FTP
or SFTP server like a local directory. Comes with an [IDE](https://github.com/tony-bringardner/fsh-ide).

### [NetworkMonitor](https://github.com/tony-bringardner/NetworkMonitor): Arduino/ESP32
Monitor and control a Wi-Fi microcontroller remotely, like the Arduino serial monitor without the
USB cable. Desktop (Java) and mobile (Flutter) clients.

## Languages I've worked in
Basic, C, C++, C#, Fortran, Pascal, Perl, bash, Tcl/Tk, JavaScript, Go, Dart, and now mostly Java.

## Say hello
Questions about Parley or protocol work? Open an issue on the relevant repo.

<sub>The older `Bjl*` repositories are archived; Parley is their successor.</sub>
