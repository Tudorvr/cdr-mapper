# CDR Mapper

A web application that plots towers from call detail record (CDR) data to a map file (kml).

Currently it accepts CDR data where the cell sites / towers and CDRs are provided in separate files but where the cell site identifiers are unique to a single network element. See 'future goals' for expansion plans for additional types of data.

## License

[MIT](https://github.com/danzek/cdr-mapper/blob/master/LICENSE), Copyright &copy; 2015 Dan O'Day

## Future Goals

 - Support simpler formats where tower location data are available in the same file and row as each CDR.
 - Add option to plot both originating and terminating cell sites / towers.
 - Accept data where towers and CDRs span multiple network elements / switches, allowing user to specify which network element names correspond to specific switch names.
 - Visually show azimuth and approximate sector coverage in map file (without committing errors of the 'granularization theory')<sup>1</sup>

----------------------------

<sub><sup>1</sup> Cf. *UNITED STATES V. ANTONIO EVANS*, 892 F. Supp2D. 949 (N.D. ILL. 2012), specifically U.S. District Judge Joan H. Lefkow's opinion and order.</sub>
