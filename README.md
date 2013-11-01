# Openbravo POS 2.30.2+bh #

Openbravo POS is a point of sale application designed for touch screens, supports ESC/POS ticket printers, customer displays and barcode scanners. It is multiuser providing product entry forms, reports and charts.

## Fork information ##

This is a fork used by #blackhats.  It has some features:

* The cards for customers and users may be editable through the standard user interface.  There is an issue with this saving properly unless you first autogenerate a code then overwrite it.
* Fixed building on JDK 7.
* Some other stuff that we'll look at adding later.

## Building ##

```
ant dist.bin
```

## Developing ##

You'll need to install a [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html).  This project targets Java 7.  You'll also need the [NetBeans IDE](https://netbeans.org/downloads/) if you want to edit forms, but it's generally advisable to use it anyway.  You only will need the Java SE version of the NetBeans IDE.



