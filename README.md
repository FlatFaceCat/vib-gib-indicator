// FlatFaceCat VIB and GIB indicator
// v1.7 ----- 12 Apr 2023
// This source code is subject to the terms of the Mozilla Public License 2.0 at https://mozilla.org/MPL/2.0/

// An indicator that will overlay the last 'x' VIB (Volume ImBalances) and GIB (Gap ImBalances) on a chart. 
// -----VIB (Volume Imbalance)-----:
// This is when there is a gap in price between the close of a candle, and the open of the next candle
// -----GIB (Gap Imbalance)-----:
// Has the same principles as a VIB, but the wick of the "next" candle is unable to close the gap of the VIB either. 


//===========Version History============
// V1.0 : Initial release 
// V1.1 : Fixed bugs related to missed gaps and bulls/bears
// v1.2 : Minor naming convention bug fix
// v1.3 : Bug fix related to issue when wick = close price 
// v1.4 : Just added more cats
// v1.5 : Corrected GIB indication candle 
// v1.6 : Correction going from Bull->Bear 
// v1.7 : Added the option to lighten or darkern borders