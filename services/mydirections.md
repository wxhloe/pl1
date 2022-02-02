# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=Toronto%2C%20ON&destination=Hamilton%2C%20ON&waypoints=%3AMississauga%2C%20ON%7Cvia%3AGuelph%2C%20ON&avoid=tolls&mode=driving&departure_time=now&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJpTvG15DL1IkRd8S0KlBVNTI",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJtwVr559GK4gR22ZZ175sFAM",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJa_upw9CaK4gRYBsjxyh7AwU",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJj3feJ2yYLIgRIQ7f2Fbuais",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.6532377,
               "lng" : -79.3779747
            },
            "southwest" : {
               "lat" : 43.2553256,
               "lng" : -80.266633
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "27.5 km",
                  "value" : 27521
               },
               "duration" : {
                  "text" : "31 mins",
                  "value" : 1867
               },
               "end_address" : "Mississauga, ON, Canada",
               "end_location" : {
                  "lat" : 43.5908795,
                  "lng" : -79.6443204
               },
               "start_address" : "Toronto, ON, Canada",
               "start_location" : {
                  "lat" : 43.6532377,
                  "lng" : -79.38273819999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1204
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 306
                     },
                     "end_location" : {
                        "lat" : 43.6431829,
                        "lng" : -79.37793119999999
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eBay St.\u003c/b\u003e toward \u003cb\u003eAlbert St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "w_miGbmocNv@UfBg@r@UHEBCDEBC@C@C@CBC@IBIBKBMHc@@G@C@E@C@C@ABC@CBAxBo@hBi@VIlA_@n@U`@MJC|Ag@b@MfA]pBo@`@M`@MBA`@M`@MHC`@OjAa@lAa@r@YRDJEXIb@ORG`@OLE`@M`@M`@Mb@M`@MTITGJEHANEVILG@?DALGJEDALEFCBC@A?A@AZODCDCNEHA"
                     },
                     "start_location" : {
                        "lat" : 43.6532377,
                        "lng" : -79.38273819999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 157
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLake Shore Blvd W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{`kiG`oncNRf@Tf@~@vB^x@DJBDHPHR"
                     },
                     "start_location" : {
                        "lat" : 43.6431829,
                        "lng" : -79.37793119999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 139
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.6417855,
                        "lng" : -79.38101999999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "s{jiGzxncN@VBV@LBLBLDNDTPf@~@fC"
                     },
                     "start_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "15.2 km",
                        "value" : 15183
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 586
                     },
                     "end_location" : {
                        "lat" : 43.6094957,
                        "lng" : -79.5548829
                     },
                     "html_instructions" : "Take the ramp onto \u003cb\u003eGardiner Expy W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "exjiGjbocNTf@f@nAd@hAh@xAJ\\Pj@^jA@B@DBLFRHV@D\\tAFXDRF\\Nl@@J@B@@@@LPRtAT`BXtBPnAHj@BZT|BD\\Nv@@HBXBVFh@PjB@LNxANbBJjAHv@Fn@?@J~@Db@Db@LpAJdA\\vDJbAJfAHr@?FBT^lEDLBd@JbAHx@Fr@Dr@Bl@D~A@dAAdBEnAK|DC|AE|A?RCxAAtA@p@?H@|@Bv@Bl@Bn@@\\FhAt@fPHfBBx@@d@Bt@Bv@@`A@v@?v@?d@?t@?zA?x@?z@@t@?\\@`@?\\@\\@\\@XDz@B\\BVB`@NzABTFZF`@XjBNx@FVRnA^lBZ`BPfAl@bD`@xBDPPfAP|@TnAHb@Hb@ZfB\\fBJl@XzA`@|BLl@?BLp@FZX~ADX@DJh@Lp@Hh@FXRjAJb@F`@Pz@?BH\\PbAFZBPFZ@FNv@F\\P|@Jp@Jl@RdA\\hBt@|D@LJl@XxABRDTJz@@@BVDZBVB^D`@@ZBX@P@h@@b@@f@@Z?f@?\\A^?XCb@Cn@AVAPC\\Gt@Iz@Ip@AFYbB]~Aa@vAK`@IRw@`CIXUr@Yz@O\\Uv@W|@Wv@g@|As@rB_@jAm@jBGRi@bBQd@{AxEw@~BcA|CCFM`@Ut@Of@Mb@Wz@Mf@Md@Sv@Kj@Qt@WfAOv@AFKl@Q`AOx@UrAQlAEZIVEXSdBS`BQ~AKdAMzAIdAEj@Ej@IjAEjAEbAEpACr@E~@E|A?RCv@?NCnBAVA`B?X?N?`@?Z?T?L@b@?H?f@?ZBpA@d@@\\@R@p@@NH`BFrAFdAH|@Dn@JlAP~AFj@Hr@Hl@L`A?BJp@Hj@Fd@BHFb@Hj@Z~A@DNz@Jb@@HJb@DNXrAXdA@DLl@n@xBBLf@`BDLBJFNDNDHBHHV@@HXj@bB\\dAf@zAX|@DJp@pBJTJVRd@Pb@`AnBTb@n@nAx@dBNZh@~@d@~@FJf@bALXNZHRXl@^~@d@hA\\z@Pf@Zt@FLJVFJTf@@?\\p@f@z@DHd@v@j@|@V`@PXnBxCbAzAJNLRNRXb@LPPRZb@~AvBLPlAbBl@|@V`@BD\\j@\\p@Xn@LZVn@Vv@Nb@J\\Jb@BNPv@Hb@V|ADXnCnQT~AV|AV~AT~ADNJ|@^|Bn@|Db@rCF`@d@~CXfBZpB^bC`@pCTrAVbBNdAb@vCl@vDBPHf@Jp@XlB^fCTzA`@|CVhBp@|ENpA^lCHr@n@~EXbCX|BBD@F@D@HFf@LhAJx@NlAPzA?Dv@|GHl@Fj@Hn@PrAJ`A`@nDJ~@n@nFV|BFn@ZjCZnCHn@Jv@Fh@ZtC^bDR~AXnCBTXxBD`@RdB@FZnCXfC@Fj@`FJ|@ZnCn@nFP~AFb@BXD`@@BFj@NrALhA`AfIFl@p@zFLfABTFp@j@fF@ZVrBXhCHt@XfCZhC`@lDJx@Df@PxAP~AHXHd@J~@ZrCHr@VjCH|@JrAF`AJtAPjCPhCRvCf@fHLjBJ|A@L@PH|@Db@Hr@Db@Hl@Fd@N~@DRHd@Ll@Hd@ZpAZdANl@Vt@Xz@d@lAb@bA@Bj@jAj@bAv@nA^j@X^l@v@xAdB|@bA`AjAvBdCn@r@dAjA"
                     },
                     "start_location" : {
                        "lat" : 43.6417855,
                        "lng" : -79.38101999999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.4 km",
                        "value" : 5419
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 192
                     },
                     "end_location" : {
                        "lat" : 43.5713036,
                        "lng" : -79.5966626
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQueen Elizabeth Way\u003c/b\u003e",
                     "polyline" : {
                        "points" : "kndiG~`qdNlAvA@@zBlC`BjBn@r@d@d@nAvAlHxHtA|Af@l@lAtANRLNj@n@V\\PPn@x@d@n@nBxBZ\\pBzBb@d@fAnAl@p@^b@DFt@~@v@~@dClC`@d@FFdAlA~BjCjD~DhCtC?@PRHHZ\\|BhCDDdBjBxCfDd@h@f@j@pFdG\\^tEhFJLx@z@jKlL~AdBfAnAJJ~AdBdAlAtGdHVZBBtAxA`AfAtC`DVXdH~HpAxAx@|@r@z@DDZ\\zFxG`CnC`JdKv@z@fCtCpD|DXZnAvAVVFFfApAdAjAzBdC|@bAt@z@dAnA~AlBX\\lCzCdBlBnAvAz@`AJJd@h@"
                     },
                     "start_location" : {
                        "lat" : 43.6094957,
                        "lng" : -79.5548829
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 432
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 43.5688399,
                        "lng" : -79.600741
                     },
                     "html_instructions" : "Take exit \u003cb\u003e132\u003c/b\u003e for \u003cb\u003eHurontario Street\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "s_}hGbfydNF^BHNRn@z@X\\JNv@dAf@l@h@~@\\n@LVR^Th@DNFXJ^J\\HTJTLZBHJRTf@HNP`@LX"
                     },
                     "start_location" : {
                        "lat" : 43.5713036,
                        "lng" : -79.5966626
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.8 km",
                        "value" : 3801
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 440
                     },
                     "end_location" : {
                        "lat" : 43.5929925,
                        "lng" : -79.6340367
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHurontario St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gp|hGr_zdNk@h@y@x@SPwAtAeBrBi@n@Sj@Y^iAbBOTo@~@MR]f@q@fAc@r@aBhC[j@q@nAU\\a@p@e@r@w@pAu@lAMVo@|@k@~@a@p@OTQXOV]l@KNg@x@]h@q@fAaA~A_AvA_@n@o@bAU^m@`AgAbBa@r@MR[d@Yf@i@|@sArBgAbBKNSZGHMV_@l@Wb@QZGJILsArBeA`BGJs@fAU^U^ILa@p@[d@g@v@{@tAOT[l@ORSHA?CBKL[b@Yb@m@~@yAtBKPcAbBaAxA[f@QX_AxA_A~Aa@n@sBlD_@l@o@~@MPuA~B]j@o@fAi@t@_AxAuCrEiAfBCBq@dAu@hAOVwB`DY`@SZkAdBaAxAiC|D_@j@a@n@gA~ASXwAlBMN[d@"
                     },
                     "start_location" : {
                        "lat" : 43.5688399,
                        "lng" : -79.600741
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 108
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 43.593604,
                        "lng" : -79.63503679999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eBurnhamthorpe Rd W\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "egaiGvo`eNK^AFCD[`@Y^]b@IPCDCHAH?F"
                     },
                     "start_location" : {
                        "lat" : 43.5929925,
                        "lng" : -79.6340367
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 336
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 43.5914867,
                        "lng" : -79.6379084
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBurnhamthorpe Rd W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_kaiG~u`eNC^x@bA`@f@X`@v@dAFFtAnBfBhCt@fA"
                     },
                     "start_location" : {
                        "lat" : 43.593604,
                        "lng" : -79.63503679999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 126
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 35
                     },
                     "end_location" : {
                        "lat" : 43.5922211,
                        "lng" : -79.6390945
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKariya Gate\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "y}`iG|gaeNGLGHe@z@g@`A[l@Wf@"
                     },
                     "start_location" : {
                        "lat" : 43.5914867,
                        "lng" : -79.6379084
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 358
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 63
                     },
                     "end_location" : {
                        "lat" : 43.58978399999999,
                        "lng" : -79.6420028
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003eCity Centre Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kbaiGhoaeN~ArBz@fA`@f@b@j@bAnAh@r@z@fAd@l@t@z@"
                     },
                     "start_location" : {
                        "lat" : 43.5922211,
                        "lng" : -79.6390945
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 224
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 43.59112469999999,
                        "lng" : -79.64407179999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMercer St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cs`iGnabeNe@t@Yb@w@zAyAnCa@n@Wf@"
                     },
                     "start_location" : {
                        "lat" : 43.58978399999999,
                        "lng" : -79.6420028
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "34 m",
                        "value" : 34
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 43.5908795,
                        "lng" : -79.6443204
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o{`iGlnbeNZ\\RR"
                     },
                     "start_location" : {
                        "lat" : 43.59112469999999,
                        "lng" : -79.64407179999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "122 km",
                  "value" : 121850
               },
               "duration" : {
                  "text" : "1 hour 39 mins",
                  "value" : 5916
               },
               "end_address" : "Hamilton, ON, Canada",
               "end_location" : {
                  "lat" : 43.2553768,
                  "lng" : -79.87027260000001
               },
               "start_address" : "Mississauga, ON, Canada",
               "start_location" : {
                  "lat" : 43.5908795,
                  "lng" : -79.6443204
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "19 m",
                        "value" : 19
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 43.5907253,
                        "lng" : -79.6442814
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e toward \u003cb\u003eMercer St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_z`iG~obeNFBB?D?JK"
                     },
                     "start_location" : {
                        "lat" : 43.5908795,
                        "lng" : -79.6443204
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "45 m",
                        "value" : 45
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 43.5909973,
                        "lng" : -79.6438749
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eMercer St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ay`iGvobeNWc@EKWa@"
                     },
                     "start_location" : {
                        "lat" : 43.5907253,
                        "lng" : -79.6442814
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 202
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 43.58978399999999,
                        "lng" : -79.6420028
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMercer St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wz`iGdmbeN`@o@xAoCv@{AXc@d@u@"
                     },
                     "start_location" : {
                        "lat" : 43.5909973,
                        "lng" : -79.6438749
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 701
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 108
                     },
                     "end_location" : {
                        "lat" : 43.5948601,
                        "lng" : -79.64010999999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCity Centre Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cs`iGnabeNu@{@e@m@{@gAi@s@cAoAc@k@a@g@{@gA_BsBMMYYMIMGOGMCOAI?O@G?aCNM@K@QBODOFMHKFGD_@d@EFININS`@}@bB"
                     },
                     "start_location" : {
                        "lat" : 43.58978399999999,
                        "lng" : -79.6420028
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 186
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 43.5961022,
                        "lng" : -79.638559
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRobert Speck Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{raiGtuaeNaAmAi@q@OWSYIKU[]a@i@y@"
                     },
                     "start_location" : {
                        "lat" : 43.5948601,
                        "lng" : -79.64010999999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 579
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 43.5998149,
                        "lng" : -79.64317079999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHurontario St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "szaiG~kaeN_@i@c@p@mAhBk@~@W^oBrCKP{AvBQVSZu@hAu@hAU\\e@x@y@hAY`@EFOT"
                     },
                     "start_location" : {
                        "lat" : 43.5961022,
                        "lng" : -79.638559
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.0 km",
                        "value" : 3021
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 116
                     },
                     "end_location" : {
                        "lat" : 43.6227763,
                        "lng" : -79.63761099999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-403 E\u003c/b\u003e via the ramp to \u003cb\u003eToronto\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "yqbiGxhbeNG?C@C?C@C@A@CBABCDEDEDEDKFIFULQHQFM@MBO?KAC?GAEAICKEECIGKI_@]]][[[[EEoAkA{@y@wAqA[[uAsAmAiAIKCAAAKKAAAAA?A?C?IBaHsHCCuKmL{@_A}@aA{CeDmBuBy@{@a@e@uC}CQQaAaAs@m@QOe@Ys@e@UMe@We@Uy@[SIk@Qc@MaASOE[G_@G}@I}@GUAg@Ak@?g@@_ABi@DSBg@FSBi@Hg@L}@Vy@Vi@R}@`@cBv@SLy@d@SLe@ZyAhAe@^SPa@^MJa@b@u@v@m@r@UZc@j@Y^eJ~M"
                     },
                     "start_location" : {
                        "lat" : 43.5998149,
                        "lng" : -79.64317079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1159
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 43.63045220000001,
                        "lng" : -79.6473318
                     },
                     "html_instructions" : "Take the \u003cb\u003eON-401 E\u003c/b\u003e exit toward \u003cb\u003eBrampton\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "kagiG`faeNKDEBC@EDGDEDGHqE`GsAdBSXCBs@`AA?W\\[b@iBdCq@|@QVA@[ZYb@OTY`@eAxAiBlCm@|@u@hAA@Yb@gA|ACDg@t@KL_@j@Y`@SZ]d@]f@QVABSXmBlCa@j@a@h@"
                     },
                     "start_location" : {
                        "lat" : 43.6227763,
                        "lng" : -79.63761099999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 592
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 43.6346681,
                        "lng" : -79.6518045
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork, follow signs for \u003cb\u003eOntario 401\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eToronto\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAirport\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "iqhiGxbceN[`@qAzAoAzAgArAs@v@iApAY\\_@`@KJe@j@g@h@kBhBiBfB}ApA"
                     },
                     "start_location" : {
                        "lat" : 43.63045220000001,
                        "lng" : -79.6473318
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.5 km",
                        "value" : 2467
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 96
                     },
                     "end_location" : {
                        "lat" : 43.6349114,
                        "lng" : -79.6730049
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to continue toward \u003cb\u003eON-401 W\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "ukiiGv~ceNYl@[d@g@f@g@h@[\\QRIH[^u@~@MNKRCDS\\CBc@|@]n@o@zAgAvC{@~BM^qApDSh@}@~Bi@vAEJs@|A?BSb@Uf@[p@CDs@pAWd@CBe@t@[f@_@f@]ZWHC?_@?C?[IWSGICCGQISEY?S?A?E?e@Fi@BIFQHOVYHEFE\\ET@PDRHHHHLDL@BZl@HTDH@BDBL@f@zAj@vAbAzC@BNd@^dA^fA`@hAn@fBnBdGnBvGlA`F|AjGLl@n@dCLj@lBxH?@Lj@@?`A~D"
                     },
                     "start_location" : {
                        "lat" : 43.6346681,
                        "lng" : -79.6518045
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2274
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 79
                     },
                     "end_location" : {
                        "lat" : 43.6250296,
                        "lng" : -79.6977282
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e, follow signs for \u003cb\u003eMavis Rd\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "emiiGfcheNbB`GHZr@zBb@rA`@nAN`@xArEpA~DRn@?@x@hCfChIhCjItArEj@lBtB~GX`A`AdD`BpFn@vBFPL`@`@tAJ\\b@zAdBrG`A~Dr@rC|AbGvAfFZ`A~BjHv@pC"
                     },
                     "start_location" : {
                        "lat" : 43.6349114,
                        "lng" : -79.6730049
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "44.4 km",
                        "value" : 44405
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1564
                     },
                     "end_location" : {
                        "lat" : 43.4498124,
                        "lng" : -80.16635819999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-401 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mogiGx}leNh@lB@BjDrLJ\\dAjDjB`GPh@tB|GjBpGv@lCRn@FVPj@Lb@ZfABJVx@x@pCxEzOdClIHXTx@BHLl@Rl@Nf@z@xCjBlGzD~MFNRp@HVL`@DLNd@fCfJpAnEFTt@hCbAnDf@`Bf@dBXb@|@`D~@fDNh@XbAT|@~@hDNh@Rr@b@~ABLh@tBFTVbAJ`@@DPp@d@jBn@`Cv@vCHXJ`@@DZnA|A~FbAvDpAlEX`AfAlDjArDRn@L`@`@pAFRFR`@pA\\|@Rl@f@|Ax@dC~@rCx@lCDJTv@^lA|AbFPj@^nAPh@DNBHDJFTpBzGn@xBV`AX~@r@xCTbARhA^lBP|@Jz@X~ATfBRbBVfCJlAFt@JrA@RBb@@`@HfAj@~MJnDNhDLvENnEFrB@b@`@dMV~Il@tQ@b@\\pKDjAn@nPRhFDtAT~FBnAN|Cd@hPH~ADnA\\|H@PDdA@ZD~B\\bIP~CNfDJrCR`DZpDb@dE@FJl@T~AP~@\\hBLl@n@tC~@zD`@|AZdA`@tARh@Lb@BDVt@L\\Rj@b@fAl@tAd@fAhAzBl@fA@Bp@lArBhDd@t@PVHJ?@t@~@rBdC`AhAv@|@TVhBtBf@j@l@p@t@z@f@h@|AfB~AjBtNvP\\f@b@f@r@x@xA`Bp@t@f@l@`ClCpC`DdBpBBBVXDDnBzB`AfAPTVZZ^hCnCBBVXBB@@hEpE~AfBVXjCzChApAbC`EvF~G`CvCX`@Z\\Z^VXfBtBnB|BnB|BjCzC`DrDxGxHpAzAfBxB|AzA`ApAnBzBtEjFzBbCn@t@VZz@~@hC|Cv@~@Z^j@l@X^@@hB~B~LrNZ\\jL|Ml@j@\\b@TVdE|ElBvBjCbDtAbB|GvHjFbGbLnMrEpFj@h@tB|BX\\X\\PTRTl@p@t@v@HJtBxB~ClD\\^r@v@v@x@`K~KTV@@DDDDBBNLPRd@b@rBbCfBtBt@z@vA~ApAzA~@jALPj@v@`@l@h@v@n@`AtAbCt@vAf@bATf@`AvBd@dA`@dAj@zAb@nAf@~A`@tAb@fB@Ff@vBZnAf@fCRlA@Dr@nE^vCd@tEp@rI`@fFTrCFz@Dp@LzANnB@JB\\@DDn@P`CNdBl@`I\\pETnCNlB?FFf@LpATnBTzAXtB^tBBL^nBFXNz@FVJb@Jb@Nj@v@xCb@zA`@pARj@n@fBPb@DLPj@Xv@Rh@JZHTFNHVHPzAhEv@|BxF`PfBbFHVVp@Tp@dBfFtAdEV|@v@vCfAzCt@vBL\\xAdEzE`NpDpJ^fAVt@Rr@b@`B^~ALr@Fb@Hj@Fb@Hv@BRJpAVrDRjDHpAXvEN`CRdE^vGDj@RpDHxALxBJfB?L@RBd@xAxW?@@JDn@Bd@LjBDlABTHlAJbBDx@JbBHpALlBLnAP~APtANz@@HHd@@HH\\Lp@ZnARv@Rp@Pj@DL`@hA^bATf@j@lAR^v@zAh@dAZj@`@t@b@z@Tb@R^BFbDfG\\p@lBpDbDdGNZj@dApD`HvB~D`AjBXh@|AvCl@jAVd@NZt@pAVd@l@jAFJNX^t@`@t@r@nA@Dt@vAXf@tAhCh@bAP\\R`@FJf@~@@@DF~@bBt@tAVb@l@|@jBnCtBjCjArAd@h@d@d@f@f@HJVRfA`A\\XLJTPJJb@ZpB|Av@j@bFzDjF`EfClBhBtAf@\\VPHF`@ZxDjCfDxB`BdA@@vBvA^T\\Vv@f@v@f@NJ^Vr@b@JH|@r@\\XHHRPPPn@n@f@j@t@~@p@`APVf@z@\\j@b@|@Zn@DJd@fANb@Rj@DJX|@ZpAXlALr@FZBNHf@NdADd@D^Fp@B\\BRBb@Dl@Bf@F~@Dv@Dv@LvCBn@D|@H|A?HBb@?@Dp@XbGV|EPlC\\bGDt@PtDHpBJdCT`FHjB@NNrBRrBL~@NbARjAPx@b@nBVz@H\\Xx@FRXv@^`A^|@t@bB~@zB^v@|@lBJTRb@HPz@nBd@fAZp@Zt@pCbGbA|BFNP`@Vj@f@fAnAnCfAfCj@jAf@hAVj@^x@h@lAVh@P^Xn@P^f@fARd@LX\\t@Vj@^x@N^R`@Zr@P`@j@nAVl@Td@z@lBh@hAXl@Vh@f@jAf@fAh@lAVj@~@rBr@|AZt@~@pBv@fBNZRf@JVd@hAPd@Tp@\\|@Tr@`@jAX~@Pn@Pn@\\lARx@XlAPx@VnAHb@Nx@Lh@BRJf@ZhBHf@Nt@TpALn@F\\@HNv@FZLr@VpAZfBJl@DTDVJn@H\\Jf@N`ALn@XzAN|@Nz@VvATlAb@`CXzAX|A@BJh@Jn@@BhAtGJh@Hb@BHJl@Hd@j@|CDXlC|NJn@FZ\\lBJl@Ln@P`AP`Ab@`C\\jBVzAFVDVj@bDDV^rB\\nBLn@XzAJn@Jl@P|@`@zBVvAJn@@@Hd@z@rEh@|C^xBTlAVvAF`@BJJp@Lz@ZdCFl@LhAFf@H`AJhAJzAJpB@RH`B?HBp@HnCDlC?\\@RDnC@t@@p@@p@@LBpCBbABjBFbEDtCTvN@p@?^@PBrC@p@?p@Bx@@rA@V?\\Bp@B`B@p@@p@BdBBzAFhEBbB@nA@b@D~B@r@?VBfBBrABrABbABlANdDBb@Bn@LbBNjBJfAB\\LpAPzAXrBRrA\\xB\\fBr@|Dh@nC`@xBLn@Lr@Jf@b@`CH`@RfAX`B~@zE^pB\\lBLp@Lp@Ll@Jl@@FRdAh@tCx@lEt@|Dj@dDb@|B`@nBd@rCH^Jh@j@|C^rBzAdIz@vEP|@d@hCJf@f@nCLr@TjAPx@Ll@Jl@RdARbAJl@?@\\lBFZLl@l@bD^pBJl@Hf@P|@\\fB^tBVrARhAFXXzAVxATfA^rBJj@H^\\jB^pBr@xDh@rC\\jBH^r@`Ef@jCX`BLl@@BNv@@Fx@tEFVn@jDRlALl@Hd@@FX~Ax@jEt@bEx@dE?BJj@?@Lj@Jl@R`Af@lCf@jCDTJl@Jj@VrA\\fBDP~A~IBLJl@nAtGN|@J^Nz@TpAt@hD`@dBJb@t@vC\\lAHXVz@X~@Rd@`@hATp@f@vAjAbDt@tBvAbEDJXv@l@dBdCfHf@rA`AvCn@jBr@pBX~@J`@t@dCt@vCp@|C@B\\dB\\jBV~ANdADV?BFd@LdAV|BNvAP~BLdBFhABn@BX@\\DlAD`BBbBBtA@xB?~B?V?X?TAb@C`GExEAtD?NCfEE|F?|@CbB?JAhCEvFCtDCpDAdB?j@?LC`EAjBExG?LA`AAnACdFC`GAT?j@?^CrBAnCCpDEdJC|E@bDDtCLdE@T?TB`@Bb@@\\Dn@BZ@T"
                     },
                     "start_location" : {
                        "lat" : 43.6250296,
                        "lng" : -79.6977282
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1133
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 43.4520696,
                        "lng" : -80.17825549999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e295\u003c/b\u003e for \u003cb\u003eON-6\u003c/b\u003e toward \u003cb\u003eGuelph\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ihehGvnhhN?|A@RL~A\\jDb@~DZnCDj@Hz@JrANzAJpABX@FDj@F|@@^?X?x@An@Ej@Ip@I`@G\\Wz@o@fBELe@pA?@Sh@Wn@_@fA[x@Wt@Sf@OZMVCBMPUXSPEBUNq@XkBr@g@REBGFIL"
                     },
                     "start_location" : {
                        "lat" : 43.4498124,
                        "lng" : -80.16635819999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.6 km",
                        "value" : 10619
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 543
                     },
                     "end_location" : {
                        "lat" : 43.5260105,
                        "lng" : -80.25758820000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eON-6 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mvehGbyjhNaHrBoCx@oF~AcBf@wGpB{Bp@eA\\iCx@MDSFMD_Bf@kA^wAf@o@ReA\\iDhAUHMDgDhA{Af@o@RGBYHsC`AiGrB}DpAaA\\ODmFdBc@PSFMD{Ah@kAb@C?u@\\q@\\_Aj@OHa@ZeAx@EBcA~@w@v@o@t@s@~@eBfCmAdBA@}@xAaAvAiBlCU^A@qH~KqBzCmGlJQXEHmEtGABo@`AY`@eBjCY`@w@jAyCpEuE~GwAxBwLtQwBbDk@z@W^wCnEcCvD{@rAuB`D}HtLgDlFuBvC_FrHgExGcEdGy@nAoFfIgCzDU\\gPxViCzDuClEwG~JYb@yBfDkC~Dw@hAkC`Eu@jAgHtKOVgA~AgBpC{AzBgBnCkAfBk@|@_@h@]f@a@h@ST[^_@b@a@b@[ZWTsAhA}ArAuBdBWReAz@mGjFQRo@h@MLg@f@a@d@{@bAAB_@d@_@f@{@nAMRaEjGWb@IJ{A~BeBjCY`@U\\y@nAuAtBkEtGYb@MTc@n@CDgAbBU^s@dAqAnBc@l@QVORUVOPOPm@l@WTQN[TYT]TsA|@MFUL}BtAOJqA|@UPCDOLe@b@e@d@W\\KH_@h@e@p@Yf@q@jAWh@EJWh@Qb@IXK`@"
                     },
                     "start_location" : {
                        "lat" : 43.4520696,
                        "lng" : -80.17825549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 410
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 43.5282941,
                        "lng" : -80.26143669999999
                     },
                     "html_instructions" : "Take the \u003cb\u003eWellington Street\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-7 E\u003c/b\u003e ramp to \u003cb\u003eCambridge\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eActon\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "qdthG|hzhNMJGFEHO`@AFaBdFa@jAWr@]~@Ut@ADSb@OZW`@STIJGD]XgAr@"
                     },
                     "start_location" : {
                        "lat" : 43.5260105,
                        "lng" : -80.25758820000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2254
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 220
                     },
                     "end_location" : {
                        "lat" : 43.5428399,
                        "lng" : -80.24354749999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-7\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yrthG~`{hNQc@Sg@[o@Wg@Ua@U]]c@e@k@y@_A]]EEo@s@_AeACCGEAAQEqByBq@s@IIw@}@g@m@[_@KOMSOSEGU]q@aAm@}@Ya@{@oAw@mA{@kAIM{@mAo@_Aq@cAg@w@eFqHWa@MWOYM[GOIYK]GYOq@Q{@Qu@YsAc@mBKi@Mk@SiAe@wCIe@?AQaAIi@Qi@IQGMGMQUOQOMKIMI[K]MuAc@o@UkCaAg@QSI]MUK]QOGq@WUMiAc@_A_@_A_@MG}B_A"
                     },
                     "start_location" : {
                        "lat" : 43.5282941,
                        "lng" : -80.26143669999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 440
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 93
                     },
                     "end_location" : {
                        "lat" : 43.5447941,
                        "lng" : -80.2481059
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWyndham St S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wmwhGdqwhNc@~BUpAu@lEg@jCG`@CJCLENELCJGLS`@ADMVILILIJIJEHEDWRi@h@k@l@"
                     },
                     "start_location" : {
                        "lat" : 43.5428399,
                        "lng" : -80.24354749999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 221
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 88
                     },
                     "end_location" : {
                        "lat" : 43.543658,
                        "lng" : -80.2503567
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMacdonell St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}ywhGtmxhNbBbE\\z@f@pAn@xAFT"
                     },
                     "start_location" : {
                        "lat" : 43.5447941,
                        "lng" : -80.2481059
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 213
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 43.5421799,
                        "lng" : -80.2488834
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eNorfolk St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{rwhGv{xhNJPb@g@Z]x@_AhAqA^a@v@_A"
                     },
                     "start_location" : {
                        "lat" : 43.543658,
                        "lng" : -80.2503567
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 893
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 88
                     },
                     "end_location" : {
                        "lat" : 43.535841,
                        "lng" : -80.255692
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWaterloo Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "siwhGnrxhNf@l@X\\zBhCrA|AhH|H~AbBtCzClG~GRR~CjD"
                     },
                     "start_location" : {
                        "lat" : 43.5421799,
                        "lng" : -80.2488834
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 185
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 43.5346386,
                        "lng" : -80.2541143
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eEdinburgh Rd S\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_bvhG`}yhNZg@jAiBp@eAr@{@`@g@"
                     },
                     "start_location" : {
                        "lat" : 43.535841,
                        "lng" : -80.255692
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1270
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 43.5267578,
                        "lng" : -80.2650682
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at the 2nd cross street onto \u003cb\u003eON-7\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ozuhGdsyhNd@@T@`@Fz@lAHLz@jAv@lAz@nAX`@l@|@p@`AT\\DFNRLRJNZ^f@l@v@|@HHp@r@pBxBJX@@\\^\\^LLdAjABBz@`ANPJLd@l@BBNT`@r@P^Th@f@vADT|@vCh@dBVx@^dAb@rAHTHVNZVj@NZl@dA"
                     },
                     "start_location" : {
                        "lat" : 43.5346386,
                        "lng" : -80.2541143
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.6 km",
                        "value" : 11637
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 581
                     },
                     "end_location" : {
                        "lat" : 43.4510751,
                        "lng" : -80.17816549999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eON-6 S\u003c/b\u003e via the ramp to \u003cb\u003eHamilton\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-401\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "githGtw{hNFZ@HBHHNHPJTHTHRDRBR@P?L?BANCLENGNGHEFIDGBIBG@E?G?IAGCCAECGEEEEIEICICIEU?MAQ@M?OD[?CF_@BUb@kDJ}@Fi@@IDm@Dk@Bw@NiCDeBFeBDcADwAF}@@WBk@De@Fs@Fu@D_@B[F_@BSNw@@M?K?]FULc@HU^mAVq@d@cAVg@Xk@^o@b@m@BERYb@i@V[d@e@r@o@PKRQRO`@Y\\W`@Wx@g@@ArAy@v@g@j@a@NMTQ\\YZY^a@NOLMLMHMX]\\e@RU|@sA|AaCdBoCr@eAT_@Vc@dCuDjEwGR[pAoB~AcC^k@|DeGr@aAt@gA`BsBx@{@DCf@i@h@k@LO`KoIHGtDaD~@w@r@o@b@c@XY@Cr@w@v@gAx@iAfC{Dt@gAz@mAhA_BdDsFNUrEaHpAoBdEqGP[NSPWxG_KFKjC}DhBsCzA}BdA_BjVc_@RYvCoE~I_NrGcKvEiHhAcBfAcBT]fBkCfDgFzA{BnDsFz@sA@?pByCx@sA`BcCj@}@b@o@bA{ApDsFjK}O|A}BnEyGr@gAlBwCXa@^i@xBgDXa@hDgFhAcBxA{BdKoOvFsIf@w@RWxAyBjC_EdBgC`@k@HIZ_@DGFGx@y@`@a@\\[f@c@|@o@|@m@n@[z@c@`A_@v@YLG@?dA]NG`@MNGvBs@bA]PENGzFmBfJ{CVIHCdFcBh@Q`@MhDiA`@Mr@Wl@Sd@O`@M`@MfDiAb@O^M`@M^M@A~Ag@RGlCy@fA_@hAYhBk@jEsAxDgArGoBVGlF}AfCu@"
                     },
                     "start_location" : {
                        "lat" : 43.5267578,
                        "lng" : -80.2650682
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.0 km",
                        "value" : 3952
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 161
                     },
                     "end_location" : {
                        "lat" : 43.4494187,
                        "lng" : -80.13942089999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork, follow signs for \u003cb\u003eON-401 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eToronto\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHamilton\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-6\u003c/b\u003e and merge onto \u003cb\u003eON-401 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-6 S\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "gpehGpxjhNn@UbA[n@SHCLC`@Kp@St@St@QbAUbA[`Bg@h@MFC`@Kn@M@?ZE^GH?PAR?N@B?RBRHDDHDNLLTHP@DDNDRBX@L?VAXG`@IZGLGLMPOLWJQFE@S?SAUIAAKEECCCKMGIGKKS?AIUI]G_@OgAG[Ii@COIm@_@sDIo@K_A_@iDSmBWyBM_AGe@ESEOGKmAyKuAmMSmBS_CK}AKaBKmB?KKuCEmCCeC?_EBoDBuD@cBFiM@q@?[@cB@_@?e@DyIBuC?o@FkJ@{@?gA@q@?eA@wABaDBuEFeJ?[?S@sBBaFDaF?cABiCBsG@_B?o@BoB?q@"
                     },
                     "start_location" : {
                        "lat" : 43.4510751,
                        "lng" : -80.17816549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1385
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 81
                     },
                     "end_location" : {
                        "lat" : 43.452375,
                        "lng" : -80.12318859999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e299\u003c/b\u003e for \u003cb\u003eBrock Road\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-6 S\u003c/b\u003e toward \u003cb\u003eHamilton\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eGuelph\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCounty Rd 46\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{eehGjfchNJuD?qAAg@Aw@Aq@Am@Ak@Cg@C}@AWCg@AYE_ASgDSeCWkCYgC]_C?ACS_@_Cc@}BYuA}@}Dm@_CG]}@qDESI_@EWEUEe@Ac@Ag@?Q?s@@_B?c@@oB?W@s@Ai@AWCWEUISGSKOMOy@gA[e@"
                     },
                     "start_location" : {
                        "lat" : 43.4494187,
                        "lng" : -80.13942089999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "25.5 km",
                        "value" : 25471
                     },
                     "duration" : {
                        "text" : "20 mins",
                        "value" : 1188
                     },
                     "end_location" : {
                        "lat" : 43.2961467,
                        "lng" : -79.89584409999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eON-6 S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kxehG|``hNXc@Vc@tBiDb@u@tA_CFKdByCd@u@DIJOzAkCz@mAhAiBXc@j@_ANWz@uA`AiBbAkBrAgCl@iAJOrAeCp@oA|AsC|AoCTc@dCmEVa@b@w@j@_Az@sAv@iAr@_AjA{A~@gAZ]PQLOj@m@\\]r@o@z@w@n@i@rB_Bv@m@hCoBf@a@^[XYTSPSTW?Af@m@\\g@f@w@RYXc@jAgBJOLS~CyErDuFrBwCZg@Zc@zBiDV]|@qALU`AwAfAkBl@wAb@_ATm@d@kABGr@wBb@yAzAuFDMd@gBXeAXgAXeAT}@?AHUXiALe@Nm@VcAJa@fB}GJa@Z_AlA}D@C`AeDnCaJJ]Pm@jAwDTu@Pm@~AiFh@kBTs@rAkETw@Ro@zAeFb@wA`@sA\\kAp@yBRm@f@gBZaAJ_@ZeAHY|@wCh@gBX_ABGBIHWFSLa@Pm@Ri@L]FQJYFO?ADKBCFSJUHS@ELWJUN[?AXk@Vi@r@sA`AkB@A^s@Zm@FMBEXm@N[Pa@Rc@Na@BGp@iBNe@@ENg@ZaABIt@_CFQ^mAXy@Vw@Pk@HWJYPe@Xy@Na@Zm@JW@CRa@JSDIP[JSNWT_@FKJQV]LSBCJOFGV]NSRUVWV[Z[\\[TSh@i@\\[\\[z@y@fD}Cn@i@t@q@zAwAt@o@n@o@l@k@DEx@y@hAmAfBqBv@cAZc@HOR]n@oAP_@JUL[JYb@qABKLc@Je@Ja@?AHc@Ls@TyATcBL_AJw@Ho@ToBZuBFe@F]Ha@Je@F]J]H]Ne@FSL]J[HS?AXs@HQJUTc@Xi@n@gAd@u@`A_Bd@u@DIT]\\g@j@_AXe@hAiBt@mA^k@f@w@`AaBt@kAR]RYlAqB^k@n@gARYDI`@o@NWVc@R[BGNUz@sAT_@@CXc@jAkBVc@Va@f@y@\\i@HMlAoBJO`A{A\\k@h@_Ab@q@Va@`A}A@C~AiC`A}AZi@NWXe@JQXe@DIHKT[LOV_@HGPSLOFIZ_@pA{At@{@|AsAvAuA^]r@o@~@}@h@g@n@q@JMfAkArA_B@?|@iAV[T[f@q@BEn@_APUr@eAj@w@`BcCl@_AXa@@AdBiCX_@?ARY\\i@r@eA@?dBkCd@s@JOl@}@\\i@^i@R]Xa@PYBCr@gAZe@BGR[r@cA`@q@NUh@u@PW^m@z@oARWr@eARYDGt@gA|@oAl@}@lAeBj@{@`AuADInBsC`@k@n@_AhAaBHMHK~@uAt@kAXa@\\i@d@o@b@q@f@u@`BcCNSd@s@\\g@nAgBTa@`AwAx@mAnAkBRY`AuAJO\\g@Xa@r@iA@?t@gAdA{AdA}A^i@TI`AuA`AsArB}CtC_EPo@f@s@l@{@Ze@t@gAZe@h@w@r@eAz@mAz@oAp@cAhAcBl@}@v@mABCV_@hAcBNUr@cAlAgBZe@t@iA`@m@`AuAz@sAx@mADGt@iANUBEr@gA\\g@d@s@Xc@LQT_@BEt@iAnAoBx@kAXc@hAeBbA}A\\g@X_@`@o@b@m@z@qAl@}@\\g@Va@jAiBf@u@jJoNvGaKrAqBl@_AdD_FHOT_@tB}CnCcEn@aAPYjAgBFI~AcCDG`AwAn@aAp@eA`AyAv@mAZc@l@aAj@{@j@{@^i@~@wADELSzA}BV_@l@}@LUr@cAfAaB`BeCbAwAb@o@l@}@LObA}APWDIbBeCv@gA?AjAgBLQ~@uAxCoEPYXc@x@mAXa@PWz@oAh@w@@Ax@oAj@y@FIr@eAZe@|BiDb@o@tB}CPYrAqBPWFIdCsDh@u@V_@JOxAyB^i@xAyBv@kA^k@Xa@vBeDFIBGhCyDzA_CR[BCr@gAR[PYvAyBdAaB~AeC|C_FTa@l@_At@iA\\i@\\g@nAkB^m@hBoCnBsC@A`CoDbEeGtDqF\\i@fBiClAkBV_@h@w@nAkBr@eAzD{FtBcD~@wA|A_CdAcB|@uA~@{AfDmFx@qAhCcEjFqIVa@bBoCfAiBjAeBdBkC`@m@x@mAn@aAhBiC\\g@rDsFv@iAx@mAr@kAhBoCT[lCaEjAgBdBkC|BoD^m@x@mAXc@\\k@DGFIXc@zCyER[zA_Cz@qAPABADGdBeCXa@~A}BNSHMFKr@iAn@aAhBsC`@o@~AgCBC~@wA`@o@Ze@Xc@LSHMZe@lBwCdA}AnCkEnAqBR[l@aAx@qAh@{@b@s@\\m@Ze@j@{@^g@b@q@f@w@\\e@\\i@X_@T]BEZe@n@aAP[t@kAt@mAp@iA^k@NUb@o@f@w@?An@eADGx@qAJQVa@JOj@_Av@mAp@iAj@}@j@}@LSJOvA{Bb@s@PYzAaCFIl@aAd@q@NWj@{@v@kAb@q@b@o@p@eAn@}@f@w@NSLQJOJOT[\\a@RSTYNOPOBCTSBALMVSNO"
                     },
                     "start_location" : {
                        "lat" : 43.452375,
                        "lng" : -80.12318859999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 km",
                        "value" : 3579
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 136
                     },
                     "end_location" : {
                        "lat" : 43.2660849,
                        "lng" : -79.89301119999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork, follow signs for \u003cb\u003eON-403 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOntario 6 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBrantford\u003c/b\u003e and merge onto \u003cb\u003eON-403 W\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "}gggG~ssfNF?@ADCZWVS^[BA|@s@p@i@|@q@`@[ZUTSFEn@a@^O\\KVEHAXEF?ZAr@@RBNBd@NZLRJPJb@\\VRXXXXpApArCxCDDVVd@`@nA`Ap@\\x@`@p@FXJRF\\HRDVDRBVDXB^BV@J?V?D?`@?b@AXCD?TC`@GZGNCZIn@Sv@[BAj@Yl@]p@g@fAcA\\]NQ@ARS`AiAb@g@jAuAPURUBCDGTWf@m@BCt@_AFEBEDGFGBC\\_@RQXY^[VQNK`@WDCDAFCRKJGTIZKTGVGXGVE^EPCD?@?@?BAN?\\AX?Z@P?R@x@D^BF@\\@D@`@B\\Dj@FNBd@FLB^DB@@?ZFD@J@|AX\\Fh@JVDj@H^BD@Z@`@?^?z@EXAjAEfAE`AE`AED?XA|@ED?j@Cb@CD?~AGf@CFAbACjAELAT?xA?P?dA@x@Br@@^BB?Z@F@T@n@Bx@Bj@Dl@BR@lERl@B`@@b@B\\B`@@pBD"
                     },
                     "start_location" : {
                        "lat" : 43.2961467,
                        "lng" : -79.89584409999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 756
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 43.2601865,
                        "lng" : -79.8906341
                     },
                     "html_instructions" : "Take the \u003cb\u003eMain St\u003c/b\u003e exit toward \u003cb\u003eON-8 E\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "_lagGhbsfNf@NNBB?d@F|BZfC^fANXDXDRBVB\\BJ@J?JAJAHALABADAJCLEJERINKFGLIRQf@c@HG^Y`@_@^YTQ`BwAVUX_@R]HUJYRy@Li@H[PY"
                     },
                     "start_location" : {
                        "lat" : 43.2660849,
                        "lng" : -79.89301119999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1701
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 191
                     },
                     "end_location" : {
                        "lat" : 43.2555998,
                        "lng" : -79.87061
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eHwy 8\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMain St W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-8\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "eg`gGlsrfNH]Hk@?ABSN_AJq@DWT{ADWl@gE|@}GXmBXsBn@uEl@iETgB^mC?Cf@oDl@mE@QBQ@M@I@M@M@IB_@Bo@@O@K@I@I@KRkAVaBn@aE^iC|@uFJo@V_BTaBj@gEH_@Hc@PkAXiBRqADWDWRqA"
                     },
                     "start_location" : {
                        "lat" : 43.2601865,
                        "lng" : -79.8906341
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "32 m",
                        "value" : 32
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 43.2553256,
                        "lng" : -79.8707187
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oj_gGhvnfNt@T"
                     },
                     "start_location" : {
                        "lat" : 43.2555998,
                        "lng" : -79.87061
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "32 m",
                        "value" : 32
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 43.2552335,
                        "lng" : -79.87034179999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yh_gG~vnfNRkA"
                     },
                     "start_location" : {
                        "lat" : 43.2553256,
                        "lng" : -79.8707187
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "17 m",
                        "value" : 17
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 43.2553768,
                        "lng" : -79.87027260000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eh_gGrtnfN]M"
                     },
                     "start_location" : {
                        "lat" : 43.2552335,
                        "lng" : -79.87034179999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 43.5447941,
                        "lng" : -80.2481059
                     },
                     "step_index" : 16,
                     "step_interpolation" : 1
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "w_miGbmocNlFkB^}A|LqExb@wMzBeAlDjGh@nC~H`U|DzTlIp{@Ild@bBlk@v@`S~Htc@`Lpn@`EtWKnOmI~[cPfg@cFhWuCzb@InPpBp[rKde@nX`o@zNdUdMzUlZzoBtd@x{DdOb_BbFrWtG`MbQjSb`@fc@f]l`@`aBhiBflAduAnIbPn@tAeA~CcKpMwSv\\sQtY}\\`i@qo@dcA}Sj[bA~D|HhMaCrE`FnGnExFNpBqA~BwBdGd@Vi@}AlE_IOqBaBuBsDwE}FaG_FVqBbB]p@}@bBaAmAy@iA]e@}BaDuDzF_KbO_DdEqCzAkHkFwz@q{@sHgDgI_AwHd@yL~E_HtFoP|TuRbWyf@`q@aTfU}P`a@oJxOuBqALaDlCi@fAvB~DbK|Oji@nTzv@h[ldA|z@hwC`h@fhBza@`wAjOrj@rF`v@hHzwBdGlqAnKdc@vKdTdJhLrk@zp@f[r]jp@dx@|m@fs@n{BlhCpTlWjK~RhGnSdG|d@hB~UzGvr@lJb]fYjy@jUjp@vCrMjFn|@bEvs@dGlYdq@rpArOlYxMpPbIrG`n@tc@|PrOnIjVnB|ZjEj{@|CfQpG|OhUxg@zLfXxPj_@bMx\\~Mbt@dVlsA|Jpj@pDr^xBfxApAlj@tJ~n@n]rkB~UdqAjW~uAhLrg@`Wnt@bGvXbBbQZ|i@mArcCxCzg@bAvLQ`J_IfT}l@tSajAx_@kJdHcOdTcp@xaAcxCdqEcO~TwIlIyQtOkLjPqYpc@qNnNuInGsElHsIvUeA~A_Cn@wDoGcPcQyWc`@iGwUoBuJmCqBmY}KwFzV_@f@aA|@v@pF|B|FdCsBhBsB~AQrObQvOrPzDbC|BoDpC_BbDnDxGxJ`PbRzKzX|DlKeBjBc@mEdCy`@tC_QbMqOdNsK~d@}r@`b@}`@ll@e}@fiCq|Dnq@gcAjHiGjIgDfm@aSd]uKfn@qQrMoBdAjB]rDkCh@_AgA{Ew_@gFkd@y@c\\l@meAj@eeAg@m]kDmXaFoTa@qS{A{BjCwGzJwPb[_j@`NaTtH{H`TmS``@km@l`@_tAr[aeArQqb@lG{P`GoInXeWdJeMrBuGrEmZbJeRb`@on@rRe[|NqPpRoTjSkZ|c@qp@x|Ao|BnpBwyCliByoCppCgfEhlAikBjKsNdJgH`FoCdENbG|EvExElFhC|Dv@`E?lFqAfGwEfKyLtH}ElIYbI|@dTl@~Po@`Qb@p]xCnFQ`L}KxGka@vGmg@vHuh@hAkHJo@hA{@IyA"
         },
         "summary" : "Gardiner Expy W",
         "warnings" : [],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
