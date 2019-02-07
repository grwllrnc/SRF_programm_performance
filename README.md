# TV ratings of the Schweizer Radio und Fernsehen (SRF)

The ratings of SRF1 and SRF2 are published on [http://www.srf.ch/medien/publikumszahlen/](http://www.srf.ch/medien/publikumszahlen/) as PDF files. This repository documents the rating in a csv file format. The dataset will be updated on a daily basis with a lag of about 4 days.

#### Description
The dataset has the following variables:

- `Beginn` *datetime*: Beginning of the program / show
- `Ende` *datetime*: End of the program / show
- `Dauer` *string*: Duration of the program / show (e.g., "1h 15'")
- `Sendungstitel` *string*: Title of the program / show
- `Untertitel` *string*: Subtitle of the program / show (if any)
- `R_T_3+` *integer*: Rating in thousand (viewers older than 3 years old)
- `MA_3+` *float*: Market share of viewers older than 3 years old (in percent)
- `R_T_15_59` *integer*: Rating in thousand (viewers between 15 and 59 years)
- `MA_15_59` *float*: Market share of viewers between 15 and 59 years (in percent)

The measurements of TV ratings in Switzerland are conducted by [Mediapulse AG](https://www.mediapulse.ch).
