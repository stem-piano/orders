# Order detail

This is a group order for a few people who joined together to exploit economy of scale in ordering fully assembled boards. It does not include sensors or pedal boards.

# Gerber files

These are exactly the same as current (at time of writing) Gerber files in the [DIY-Grand-Digital-Piano](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/main/hardware/releases/)

However I am including them here because the vendor wants them zipped (and hence it's a small change compared to what it's there) and because they will
likely change on the main repo as new things are introduced (I guess the second one can be solved with the permalinks I am providing below anyway, but
since the files are small I see the convenience of collecting everything like it has been ordered)

* [ACE board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/aceA00/aceA00_gerber)
* [SCA board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/sca00/sca00_gerber)
* [IPS board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/ips20/ips20_gerber)


# Position files

For the automated assembly/soldering, a file specifying the position of all components is needed. These have been generated from the KiCad files with some minimal changes,
so they are **not** exactly what comes out from the KiCad releases linked below. The most important changes have been [PR71](https://github.com/gzweigle/DIY-Grand-Digital-Piano/pull/71)
and [PR72](https://github.com/gzweigle/DIY-Grand-Digital-Piano/pull/72)

Also, PCBWay accepts only one position file per board, but the ACE and SCA boards have components located on both sides. So a zip file of its content is provided :-(
For the IPS board, components need to be soldered only on one side, hence a more convenient to use (text-based) file is provided instead.

* [ACE board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/aceA00/aceA00_kicad_v1)
* [SCA board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/sca00/sca00_kicad_v0)
* [IPS board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/tree/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/ips20/ips20_kicad_v0)


# Bill of Materials

These were based off the original text files which are included in the links, but then needed to be modified to the format PCBWay wanted, which unfortunately is microsoft EXCEL
and hence cannot be easily diff'ed in git.

* [ACE board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/blob/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/aceA00/aceA00_bill_of_materials_0.txt)
* [SCA board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/blob/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/sca00/sca00_bill_of_materials_0.txt)
* [IPS board](https://github.com/gzweigle/DIY-Grand-Digital-Piano/blob/51ad6b66555ceca2a08ab771cdea9e55334bccfc/hardware/releases/ips20/ips20_bill_of_materials_0.txt)
