**Table:** Testing overidentifying assumptions (wholesale, business days, hours 11-15)<br>*For grid company EnergiMidt (DK1)*<br><html><table>
<tr><td>                    </td><td>(1) P2SLS, wp only   </td><td>(2) POLS, y = uhat(wp)   </td><td>(3) P2SLS, wp_other only   </td><td>(4) POLS, y = uhat(wp_other)   </td><td>(5) P2SLS, both   </td><td>(6) OLS, y = uhat(both)   </td></tr>
<tr><td>                    </td><td>        b/se   </td><td>        b/se   </td><td>        b/se   </td><td>        b/se   </td><td>        b/se   </td><td>        b/se   </td></tr>
<tr><td>log spot price      </td><td>-0.07394***<br>(0.00830)   </td><td>        <br>   </td><td>-0.08265***<br>(0.00860)   </td><td>        <br>   </td><td>-0.07786***<br>(0.00821)   </td><td>        <br>   </td></tr>
<tr><td>log wholesale meters</td><td>0.65226***<br>(0.11281)   </td><td>-0.00000<br>(0.11493)   </td><td>0.64678***<br>(0.11461)   </td><td>-0.00000<br>(0.11693)   </td><td>0.64979***<br>(0.11358)   </td><td>0.00451<br>(0.11559)   </td></tr>
<tr><td>Temperature         </td><td>-0.00541***<br>(0.00069)   </td><td>0.00000<br>(0.00063)   </td><td>-0.00572***<br>(0.00070)   </td><td>0.00000<br>(0.00064)   </td><td>-0.00554***<br>(0.00069)   </td><td>0.00007<br>(0.00064)   </td></tr>
<tr><td>Temperature squared </td><td>0.00022***<br>(0.00003)   </td><td>-0.00000<br>(0.00002)   </td><td>0.00023***<br>(0.00003)   </td><td>-0.00000<br>(0.00002)   </td><td>0.00022***<br>(0.00003)   </td><td>-0.00000<br>(0.00002)   </td></tr>
<tr><td>Time trend          </td><td>-0.01251***<br>(0.00129)   </td><td>-0.00000<br>(0.00131)   </td><td>-0.01247***<br>(0.00131)   </td><td>-0.00000<br>(0.00133)   </td><td>-0.01249***<br>(0.00130)   </td><td>0.00006<br>(0.00132)   </td></tr>
<tr><td>year=2016           </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td></tr>
<tr><td>year=2017           </td><td>4.57219***<br>(0.46921)   </td><td>0.00005<br>(0.47797)   </td><td>4.55585***<br>(0.47545)   </td><td>0.00014<br>(0.48426)   </td><td>4.56488***<br>(0.47187)   </td><td>-0.02041<br>(0.48077)   </td></tr>
<tr><td>year=2018           </td><td>9.63268***<br>(0.94250)   </td><td>0.00010<br>(0.96008)   </td><td>9.60805***<br>(0.95550)   </td><td>0.00029<br>(0.97316)   </td><td>9.62169***<br>(0.94806)   </td><td>-0.04534<br>(0.96631)   </td></tr>
<tr><td>week=1              </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td></tr>
<tr><td>week=2              </td><td>0.13759***<br>(0.01975)   </td><td>0.00000<br>(0.01950)   </td><td>0.14404***<br>(0.02049)   </td><td>0.00000<br>(0.02078)   </td><td>0.14049***<br>(0.02004)   </td><td>0.00093<br>(0.01997)   </td></tr>
<tr><td>week=3              </td><td>0.20392***<br>(0.02449)   </td><td>0.00000<br>(0.02471)   </td><td>0.20861***<br>(0.02521)   </td><td>0.00001<br>(0.02579)   </td><td>0.20603***<br>(0.02479)   </td><td>-0.00052<br>(0.02516)   </td></tr>
<tr><td>week=4              </td><td>0.27987***<br>(0.03107)   </td><td>0.00000<br>(0.03157)   </td><td>0.28215***<br>(0.03190)   </td><td>0.00001<br>(0.03256)   </td><td>0.28090***<br>(0.03143)   </td><td>0.00109<br>(0.03196)   </td></tr>
<tr><td>week=5              </td><td>0.35408***<br>(0.03881)   </td><td>0.00000<br>(0.03951)   </td><td>0.35629***<br>(0.03963)   </td><td>0.00001<br>(0.04046)   </td><td>0.35508***<br>(0.03916)   </td><td>-0.00201<br>(0.03998)   </td></tr>
<tr><td>week=6              </td><td>0.41138***<br>(0.04787)   </td><td>0.00000<br>(0.04874)   </td><td>0.41553***<br>(0.04863)   </td><td>0.00001<br>(0.04969)   </td><td>0.41325***<br>(0.04819)   </td><td>-0.00290<br>(0.04919)   </td></tr>
<tr><td>week=7              </td><td>0.44013***<br>(0.05629)   </td><td>0.00001<br>(0.05737)   </td><td>0.44182***<br>(0.05718)   </td><td>0.00002<br>(0.05834)   </td><td>0.44090***<br>(0.05667)   </td><td>-0.00283<br>(0.05782)   </td></tr>
<tr><td>week=8              </td><td>0.57245***<br>(0.06499)   </td><td>0.00001<br>(0.06621)   </td><td>0.57465***<br>(0.06592)   </td><td>0.00002<br>(0.06724)   </td><td>0.57345***<br>(0.06539)   </td><td>-0.00409<br>(0.06675)   </td></tr>
<tr><td>week=9              </td><td>0.64910***<br>(0.07307)   </td><td>0.00001<br>(0.07444)   </td><td>0.64906***<br>(0.07417)   </td><td>0.00002<br>(0.07557)   </td><td>0.64909***<br>(0.07354)   </td><td>-0.00417<br>(0.07504)   </td></tr>
<tr><td>week=10             </td><td>0.73969***<br>(0.08159)   </td><td>0.00001<br>(0.08313)   </td><td>0.74181***<br>(0.08271)   </td><td>0.00002<br>(0.08433)   </td><td>0.74065***<br>(0.08207)   </td><td>-0.00613<br>(0.08378)   </td></tr>
<tr><td>week=11             </td><td>0.82168***<br>(0.09021)   </td><td>0.00001<br>(0.09190)   </td><td>0.82193***<br>(0.09150)   </td><td>0.00003<br>(0.09323)   </td><td>0.82180***<br>(0.09077)   </td><td>-0.00502<br>(0.09255)   </td></tr>
<tr><td>week=12             </td><td>0.86826***<br>(0.09933)   </td><td>0.00001<br>(0.10121)   </td><td>0.86911***<br>(0.10071)   </td><td>0.00003<br>(0.10263)   </td><td>0.86865***<br>(0.09992)   </td><td>-0.00510<br>(0.10188)   </td></tr>
<tr><td>week=13             </td><td>0.97093***<br>(0.10796)   </td><td>0.00001<br>(0.10999)   </td><td>0.97146***<br>(0.10943)   </td><td>0.00003<br>(0.11151)   </td><td>0.97117***<br>(0.10859)   </td><td>-0.00650<br>(0.11074)   </td></tr>
<tr><td>week=14             </td><td>1.12758***<br>(0.11660)   </td><td>0.00001<br>(0.11873)   </td><td>1.13184***<br>(0.11811)   </td><td>0.00003<br>(0.12035)   </td><td>1.12950***<br>(0.11724)   </td><td>-0.00778<br>(0.11952)   </td></tr>
<tr><td>week=15             </td><td>1.20928***<br>(0.12551)   </td><td>0.00001<br>(0.12774)   </td><td>1.21498***<br>(0.12708)   </td><td>0.00004<br>(0.12949)   </td><td>1.21186***<br>(0.12618)   </td><td>-0.00897<br>(0.12867)   </td></tr>
<tr><td>week=16             </td><td>1.28278***<br>(0.13385)   </td><td>0.00001<br>(0.13634)   </td><td>1.28636***<br>(0.13557)   </td><td>0.00004<br>(0.13817)   </td><td>1.28440***<br>(0.13458)   </td><td>-0.00831<br>(0.13724)   </td></tr>
<tr><td>week=17             </td><td>1.39480***<br>(0.14400)   </td><td>0.00002<br>(0.14666)   </td><td>1.39791***<br>(0.14576)   </td><td>0.00004<br>(0.14852)   </td><td>1.39622***<br>(0.14475)   </td><td>-0.00843<br>(0.14760)   </td></tr>
<tr><td>week=18             </td><td>1.27341***<br>(0.15321)   </td><td>0.00002<br>(0.15493)   </td><td>1.25461***<br>(0.15594)   </td><td>0.00005<br>(0.15729)   </td><td>1.26497***<br>(0.15433)   </td><td>-0.01012<br>(0.15608)   </td></tr>
<tr><td>week=19             </td><td>1.44142***<br>(0.16178)   </td><td>0.00002<br>(0.16409)   </td><td>1.42866***<br>(0.16442)   </td><td>0.00005<br>(0.16659)   </td><td>1.43570***<br>(0.16289)   </td><td>-0.01028<br>(0.16515)   </td></tr>
<tr><td>week=20             </td><td>1.52976***<br>(0.17062)   </td><td>0.00002<br>(0.17300)   </td><td>1.51554***<br>(0.17336)   </td><td>0.00005<br>(0.17559)   </td><td>1.52338***<br>(0.17177)   </td><td>-0.01068<br>(0.17411)   </td></tr>
<tr><td>week=21             </td><td>1.62959***<br>(0.17939)   </td><td>0.00002<br>(0.18196)   </td><td>1.61493***<br>(0.18221)   </td><td>0.00005<br>(0.18463)   </td><td>1.62301***<br>(0.18058)   </td><td>-0.01151<br>(0.18310)   </td></tr>
<tr><td>week=22             </td><td>1.71414***<br>(0.18799)   </td><td>0.00002<br>(0.19076)   </td><td>1.69951***<br>(0.19089)   </td><td>0.00006<br>(0.19353)   </td><td>1.70758***<br>(0.18921)   </td><td>-0.01391<br>(0.19201)   </td></tr>
<tr><td>week=23             </td><td>1.84034***<br>(0.19654)   </td><td>0.00002<br>(0.19967)   </td><td>1.82735***<br>(0.19951)   </td><td>0.00006<br>(0.20254)   </td><td>1.83451***<br>(0.19779)   </td><td>-0.01589<br>(0.20100)   </td></tr>
<tr><td>week=24             </td><td>1.94017***<br>(0.20508)   </td><td>0.00002<br>(0.20844)   </td><td>1.92752***<br>(0.20812)   </td><td>0.00006<br>(0.21139)   </td><td>1.93450***<br>(0.20637)   </td><td>-0.01635<br>(0.20979)   </td></tr>
<tr><td>week=25             </td><td>2.00750***<br>(0.21400)   </td><td>0.00002<br>(0.21751)   </td><td>1.99437***<br>(0.21716)   </td><td>0.00006<br>(0.22058)   </td><td>2.00161***<br>(0.21534)   </td><td>-0.01612<br>(0.21890)   </td></tr>
<tr><td>week=26             </td><td>2.10268***<br>(0.22347)   </td><td>0.00002<br>(0.22724)   </td><td>2.09003***<br>(0.22669)   </td><td>0.00007<br>(0.23038)   </td><td>2.09701***<br>(0.22483)   </td><td>-0.01752<br>(0.22871)   </td></tr>
<tr><td>week=27             </td><td>2.22192***<br>(0.23254)   </td><td>0.00002<br>(0.23644)   </td><td>2.20765***<br>(0.23582)   </td><td>0.00007<br>(0.23970)   </td><td>2.21552***<br>(0.23393)   </td><td>-0.01902<br>(0.23797)   </td></tr>
<tr><td>week=28             </td><td>2.30134***<br>(0.24091)   </td><td>0.00003<br>(0.24519)   </td><td>2.29166***<br>(0.24431)   </td><td>0.00007<br>(0.24854)   </td><td>2.29701***<br>(0.24236)   </td><td>-0.01854<br>(0.24679)   </td></tr>
<tr><td>week=29             </td><td>2.23712***<br>(0.25010)   </td><td>0.00003<br>(0.25453)   </td><td>2.22669***<br>(0.25358)   </td><td>0.00007<br>(0.25798)   </td><td>2.23245***<br>(0.25158)   </td><td>-0.01913<br>(0.25615)   </td></tr>
<tr><td>week=30             </td><td>2.29830***<br>(0.25886)   </td><td>0.00003<br>(0.26346)   </td><td>2.28762***<br>(0.26243)   </td><td>0.00008<br>(0.26701)   </td><td>2.29352***<br>(0.26038)   </td><td>-0.02046<br>(0.26515)   </td></tr>
<tr><td>week=31             </td><td>2.45287***<br>(0.26744)   </td><td>0.00003<br>(0.27214)   </td><td>2.44069***<br>(0.27112)   </td><td>0.00008<br>(0.27580)   </td><td>2.44742***<br>(0.26900)   </td><td>-0.01922<br>(0.27384)   </td></tr>
<tr><td>week=32             </td><td>2.69109***<br>(0.27618)   </td><td>0.00003<br>(0.28115)   </td><td>2.68109***<br>(0.27991)   </td><td>0.00008<br>(0.28491)   </td><td>2.68662***<br>(0.27777)   </td><td>-0.02064<br>(0.28283)   </td></tr>
<tr><td>week=33             </td><td>2.80884***<br>(0.28490)   </td><td>0.00003<br>(0.29009)   </td><td>2.80003***<br>(0.28875)   </td><td>0.00009<br>(0.29396)   </td><td>2.80490***<br>(0.28654)   </td><td>-0.02075<br>(0.29188)   </td></tr>
<tr><td>week=34             </td><td>2.91115***<br>(0.29388)   </td><td>0.00003<br>(0.29925)   </td><td>2.90273***<br>(0.29784)   </td><td>0.00009<br>(0.30324)   </td><td>2.90739***<br>(0.29557)   </td><td>-0.02113<br>(0.30108)   </td></tr>
<tr><td>week=35             </td><td>2.99226***<br>(0.30276)   </td><td>0.00003<br>(0.30829)   </td><td>2.98322***<br>(0.30685)   </td><td>0.00009<br>(0.31240)   </td><td>2.98822***<br>(0.30451)   </td><td>-0.02110<br>(0.31019)   </td></tr>
<tr><td>week=36             </td><td>3.11233***<br>(0.31141)   </td><td>0.00003<br>(0.31715)   </td><td>3.10447***<br>(0.31560)   </td><td>0.00009<br>(0.32137)   </td><td>3.10882***<br>(0.31320)   </td><td>-0.02251<br>(0.31914)   </td></tr>
<tr><td>week=37             </td><td>3.20373***<br>(0.32034)   </td><td>0.00003<br>(0.32626)   </td><td>3.19620***<br>(0.32462)   </td><td>0.00010<br>(0.33058)   </td><td>3.20037***<br>(0.32217)   </td><td>-0.02402<br>(0.32829)   </td></tr>
<tr><td>week=38             </td><td>3.28355***<br>(0.32902)   </td><td>0.00003<br>(0.33513)   </td><td>3.27700***<br>(0.33342)   </td><td>0.00010<br>(0.33958)   </td><td>3.28063***<br>(0.33090)   </td><td>-0.02306<br>(0.33722)   </td></tr>
<tr><td>week=39             </td><td>3.38741***<br>(0.33817)   </td><td>0.00004<br>(0.34441)   </td><td>3.37881***<br>(0.34268)   </td><td>0.00010<br>(0.34896)   </td><td>3.38357***<br>(0.34009)   </td><td>-0.02313<br>(0.34652)   </td></tr>
<tr><td>week=40             </td><td>3.12439***<br>(0.35608)   </td><td>0.00004<br>(0.36259)   </td><td>3.10793***<br>(0.36079)   </td><td>0.00011<br>(0.36723)   </td><td>3.11702***<br>(0.35808)   </td><td>-0.01131<br>(0.36464)   </td></tr>
<tr><td>week=41             </td><td>3.20352***<br>(0.36426)   </td><td>0.00004<br>(0.37098)   </td><td>3.19015***<br>(0.36904)   </td><td>0.00011<br>(0.37576)   </td><td>3.19754***<br>(0.36629)   </td><td>-0.01158<br>(0.37305)   </td></tr>
<tr><td>week=42             </td><td>3.24662***<br>(0.37331)   </td><td>0.00004<br>(0.38024)   </td><td>3.23400***<br>(0.37821)   </td><td>0.00011<br>(0.38513)   </td><td>3.24097***<br>(0.37540)   </td><td>-0.01051<br>(0.38239)   </td></tr>
<tr><td>week=43             </td><td>3.38490***<br>(0.38234)   </td><td>0.00004<br>(0.38942)   </td><td>3.37102***<br>(0.38738)   </td><td>0.00011<br>(0.39444)   </td><td>3.37869***<br>(0.38448)   </td><td>-0.01268<br>(0.39164)   </td></tr>
<tr><td>week=44             </td><td>3.44099***<br>(0.39118)   </td><td>0.00004<br>(0.39840)   </td><td>3.42618***<br>(0.39635)   </td><td>0.00012<br>(0.40354)   </td><td>3.43436***<br>(0.39338)   </td><td>-0.01434<br>(0.40069)   </td></tr>
<tr><td>week=45             </td><td>3.57810***<br>(0.39991)   </td><td>0.00004<br>(0.40736)   </td><td>3.56519***<br>(0.40522)   </td><td>0.00012<br>(0.41267)   </td><td>3.57233***<br>(0.40217)   </td><td>-0.01506<br>(0.40971)   </td></tr>
<tr><td>week=46             </td><td>3.66428***<br>(0.40879)   </td><td>0.00004<br>(0.41642)   </td><td>3.65271***<br>(0.41422)   </td><td>0.00012<br>(0.42185)   </td><td>3.65911***<br>(0.41111)   </td><td>-0.01436<br>(0.41884)   </td></tr>
<tr><td>week=47             </td><td>3.77048***<br>(0.41794)   </td><td>0.00004<br>(0.42576)   </td><td>3.75911***<br>(0.42347)   </td><td>0.00013<br>(0.43130)   </td><td>3.76541***<br>(0.42030)   </td><td>-0.01537<br>(0.42823)   </td></tr>
<tr><td>week=48             </td><td>3.85801***<br>(0.42680)   </td><td>0.00005<br>(0.43475)   </td><td>3.84612***<br>(0.43246)   </td><td>0.00013<br>(0.44042)   </td><td>3.85270***<br>(0.42922)   </td><td>-0.01682<br>(0.43726)   </td></tr>
<tr><td>week=49             </td><td>4.00163***<br>(0.43454)   </td><td>0.00005<br>(0.44269)   </td><td>3.98988***<br>(0.44030)   </td><td>0.00013<br>(0.44845)   </td><td>3.99638***<br>(0.43700)   </td><td>-0.01824<br>(0.44532)   </td></tr>
<tr><td>week=50             </td><td>4.09339***<br>(0.44371)   </td><td>0.00005<br>(0.45207)   </td><td>4.08366***<br>(0.44955)   </td><td>0.00013<br>(0.45796)   </td><td>4.08906***<br>(0.44621)   </td><td>-0.01911<br>(0.45472)   </td></tr>
<tr><td>week=51             </td><td>4.11657***<br>(0.45253)   </td><td>0.00005<br>(0.46102)   </td><td>4.10704***<br>(0.45849)   </td><td>0.00014<br>(0.46702)   </td><td>4.11232***<br>(0.45508)   </td><td>-0.01671<br>(0.46370)   </td></tr>
<tr><td>week=52             </td><td>0.00000<br>(.)   </td><td>        <br>   </td><td>0.00000<br>(.)   </td><td>        <br>   </td><td>0.00000<br>(.)   </td><td>        <br>   </td></tr>
<tr><td>week=53             </td><td>0.00000<br>(.)   </td><td>        <br>   </td><td>0.00000<br>(.)   </td><td>        <br>   </td><td>0.00000<br>(.)   </td><td>        <br>   </td></tr>
<tr><td>day_bd=1 # hour=11  </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td></tr>
<tr><td>day_bd=1 # hour=12  </td><td>0.03504***<br>(0.00745)   </td><td>-0.00000<br>(0.00759)   </td><td>0.03498***<br>(0.00754)   </td><td>-0.00000<br>(0.00768)   </td><td>0.03501***<br>(0.00749)   </td><td>0.00001<br>(0.00762)   </td></tr>
<tr><td>day_bd=1 # hour=13  </td><td>0.10059***<br>(0.00784)   </td><td>-0.00000<br>(0.00797)   </td><td>0.10088***<br>(0.00793)   </td><td>-0.00000<br>(0.00806)   </td><td>0.10072***<br>(0.00788)   </td><td>-0.00001<br>(0.00801)   </td></tr>
<tr><td>day_bd=1 # hour=14  </td><td>0.15363***<br>(0.00828)   </td><td>-0.00000<br>(0.00839)   </td><td>0.15427***<br>(0.00837)   </td><td>-0.00000<br>(0.00848)   </td><td>0.15391***<br>(0.00832)   </td><td>-0.00001<br>(0.00842)   </td></tr>
<tr><td>day_bd=1 # hour=15  </td><td>0.14275***<br>(0.00932)   </td><td>-0.00000<br>(0.00947)   </td><td>0.14355***<br>(0.00944)   </td><td>-0.00000<br>(0.00957)   </td><td>0.14311***<br>(0.00937)   </td><td>-0.00002<br>(0.00951)   </td></tr>
<tr><td>day_bd=2 # hour=11  </td><td>0.01648***<br>(0.00463)   </td><td>-0.00000<br>(0.00472)   </td><td>0.01656***<br>(0.00470)   </td><td>-0.00000<br>(0.00480)   </td><td>0.01652***<br>(0.00466)   </td><td>0.00043<br>(0.00476)   </td></tr>
<tr><td>day_bd=2 # hour=12  </td><td>0.05224***<br>(0.00690)   </td><td>-0.00000<br>(0.00704)   </td><td>0.05245***<br>(0.00700)   </td><td>-0.00000<br>(0.00713)   </td><td>0.05234***<br>(0.00694)   </td><td>0.00042<br>(0.00706)   </td></tr>
<tr><td>day_bd=2 # hour=13  </td><td>0.11085***<br>(0.00662)   </td><td>-0.00000<br>(0.00675)   </td><td>0.11121***<br>(0.00672)   </td><td>-0.00000<br>(0.00684)   </td><td>0.11101***<br>(0.00666)   </td><td>0.00037<br>(0.00677)   </td></tr>
<tr><td>day_bd=2 # hour=14  </td><td>0.16274***<br>(0.00712)   </td><td>-0.00000<br>(0.00725)   </td><td>0.16330***<br>(0.00723)   </td><td>-0.00000<br>(0.00736)   </td><td>0.16300***<br>(0.00717)   </td><td>0.00042<br>(0.00728)   </td></tr>
<tr><td>day_bd=2 # hour=15  </td><td>0.15821***<br>(0.00836)   </td><td>-0.00000<br>(0.00853)   </td><td>0.15878***<br>(0.00847)   </td><td>-0.00000<br>(0.00863)   </td><td>0.15847***<br>(0.00841)   </td><td>0.00039<br>(0.00859)   </td></tr>
<tr><td>day_bd=3 # hour=11  </td><td>0.03199***<br>(0.00531)   </td><td>0.00000<br>(0.00542)   </td><td>0.03171***<br>(0.00552)   </td><td>0.00000<br>(0.00564)   </td><td>0.03186***<br>(0.00540)   </td><td>0.00021<br>(0.00553)   </td></tr>
<tr><td>day_bd=3 # hour=12  </td><td>0.07016***<br>(0.00696)   </td><td>-0.00000<br>(0.00711)   </td><td>0.06985***<br>(0.00713)   </td><td>-0.00000<br>(0.00729)   </td><td>0.07002***<br>(0.00704)   </td><td>0.00019<br>(0.00717)   </td></tr>
<tr><td>day_bd=3 # hour=13  </td><td>0.13353***<br>(0.00754)   </td><td>-0.00000<br>(0.00769)   </td><td>0.13331***<br>(0.00768)   </td><td>-0.00000<br>(0.00785)   </td><td>0.13343***<br>(0.00760)   </td><td>0.00016<br>(0.00774)   </td></tr>
<tr><td>day_bd=3 # hour=14  </td><td>0.18282***<br>(0.00778)   </td><td>-0.00000<br>(0.00793)   </td><td>0.18280***<br>(0.00794)   </td><td>-0.00000<br>(0.00809)   </td><td>0.18281***<br>(0.00785)   </td><td>0.00012<br>(0.00798)   </td></tr>
<tr><td>day_bd=3 # hour=15  </td><td>0.17385***<br>(0.00852)   </td><td>-0.00000<br>(0.00868)   </td><td>0.17424***<br>(0.00861)   </td><td>-0.00000<br>(0.00875)   </td><td>0.17402***<br>(0.00856)   </td><td>0.00003<br>(0.00870)   </td></tr>
<tr><td>day_bd=4 # hour=11  </td><td>0.03732***<br>(0.00528)   </td><td>0.00000<br>(0.00539)   </td><td>0.03685***<br>(0.00546)   </td><td>0.00000<br>(0.00558)   </td><td>0.03711***<br>(0.00536)   </td><td>0.00038<br>(0.00548)   </td></tr>
<tr><td>day_bd=4 # hour=12  </td><td>0.07555***<br>(0.00677)   </td><td>-0.00000<br>(0.00690)   </td><td>0.07511***<br>(0.00692)   </td><td>-0.00000<br>(0.00706)   </td><td>0.07535***<br>(0.00684)   </td><td>0.00038<br>(0.00696)   </td></tr>
<tr><td>day_bd=4 # hour=13  </td><td>0.13310***<br>(0.00731)   </td><td>-0.00000<br>(0.00747)   </td><td>0.13265***<br>(0.00754)   </td><td>-0.00000<br>(0.00770)   </td><td>0.13289***<br>(0.00741)   </td><td>0.00037<br>(0.00755)   </td></tr>
<tr><td>day_bd=4 # hour=14  </td><td>0.17859***<br>(0.00742)   </td><td>-0.00000<br>(0.00756)   </td><td>0.17841***<br>(0.00765)   </td><td>-0.00000<br>(0.00780)   </td><td>0.17851***<br>(0.00752)   </td><td>0.00043<br>(0.00765)   </td></tr>
<tr><td>day_bd=4 # hour=15  </td><td>0.16958***<br>(0.00882)   </td><td>-0.00000<br>(0.00898)   </td><td>0.16945***<br>(0.00904)   </td><td>-0.00000<br>(0.00921)   </td><td>0.16952***<br>(0.00891)   </td><td>0.00037<br>(0.00910)   </td></tr>
<tr><td>month=1 # hour=11   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td></tr>
<tr><td>month=1 # hour=12   </td><td>-0.08248***<br>(0.01430)   </td><td>0.00000<br>(0.01456)   </td><td>-0.08273***<br>(0.01493)   </td><td>0.00000<br>(0.01521)   </td><td>-0.08259***<br>(0.01458)   </td><td>0.00001<br>(0.01483)   </td></tr>
<tr><td>month=1 # hour=13   </td><td>-0.12966***<br>(0.01356)   </td><td>0.00000<br>(0.01383)   </td><td>-0.13015***<br>(0.01421)   </td><td>0.00000<br>(0.01449)   </td><td>-0.12988***<br>(0.01385)   </td><td>0.00002<br>(0.01410)   </td></tr>
<tr><td>month=1 # hour=14   </td><td>-0.21978***<br>(0.01356)   </td><td>0.00000<br>(0.01382)   </td><td>-0.22063***<br>(0.01423)   </td><td>0.00000<br>(0.01450)   </td><td>-0.22016***<br>(0.01386)   </td><td>0.00005<br>(0.01411)   </td></tr>
<tr><td>month=1 # hour=15   </td><td>-0.29194***<br>(0.01414)   </td><td>0.00000<br>(0.01441)   </td><td>-0.29286***<br>(0.01480)   </td><td>0.00000<br>(0.01507)   </td><td>-0.29236***<br>(0.01443)   </td><td>0.00016<br>(0.01470)   </td></tr>
<tr><td>month=2 # hour=11   </td><td>0.04658***<br>(0.01559)   </td><td>0.00000<br>(0.01590)   </td><td>0.04645***<br>(0.01578)   </td><td>0.00000<br>(0.01609)   </td><td>0.04653***<br>(0.01567)   </td><td>0.00177<br>(0.01605)   </td></tr>
<tr><td>month=2 # hour=12   </td><td>-0.02976*<br>(0.01553)   </td><td>0.00000<br>(0.01585)   </td><td>-0.03010*<br>(0.01572)   </td><td>0.00000<br>(0.01605)   </td><td>-0.02991*<br>(0.01561)   </td><td>0.00193<br>(0.01600)   </td></tr>
<tr><td>month=2 # hour=13   </td><td>-0.06625***<br>(0.01677)   </td><td>0.00000<br>(0.01713)   </td><td>-0.06691***<br>(0.01690)   </td><td>0.00000<br>(0.01728)   </td><td>-0.06655***<br>(0.01682)   </td><td>0.00200<br>(0.01725)   </td></tr>
<tr><td>month=2 # hour=14   </td><td>-0.15844***<br>(0.01694)   </td><td>0.00000<br>(0.01734)   </td><td>-0.15942***<br>(0.01708)   </td><td>0.00000<br>(0.01748)   </td><td>-0.15888***<br>(0.01699)   </td><td>0.00195<br>(0.01746)   </td></tr>
<tr><td>month=2 # hour=15   </td><td>-0.23776***<br>(0.01679)   </td><td>0.00000<br>(0.01717)   </td><td>-0.23885***<br>(0.01695)   </td><td>0.00000<br>(0.01735)   </td><td>-0.23825***<br>(0.01686)   </td><td>0.00201<br>(0.01729)   </td></tr>
<tr><td>month=3 # hour=11   </td><td>0.06168***<br>(0.01931)   </td><td>0.00000<br>(0.01965)   </td><td>0.06193***<br>(0.01945)   </td><td>0.00000<br>(0.01978)   </td><td>0.06180***<br>(0.01937)   </td><td>0.00312<br>(0.02002)   </td></tr>
<tr><td>month=3 # hour=12   </td><td>-0.01550<br>(0.02067)   </td><td>0.00000<br>(0.02106)   </td><td>-0.01550<br>(0.02074)   </td><td>0.00000<br>(0.02113)   </td><td>-0.01550<br>(0.02069)   </td><td>0.00320<br>(0.02137)   </td></tr>
<tr><td>month=3 # hour=13   </td><td>-0.05669***<br>(0.02051)   </td><td>0.00000<br>(0.02092)   </td><td>-0.05694***<br>(0.02059)   </td><td>0.00000<br>(0.02100)   </td><td>-0.05680***<br>(0.02054)   </td><td>0.00319<br>(0.02121)   </td></tr>
<tr><td>month=3 # hour=14   </td><td>-0.14853***<br>(0.02081)   </td><td>0.00000<br>(0.02124)   </td><td>-0.14915***<br>(0.02088)   </td><td>0.00000<br>(0.02132)   </td><td>-0.14881***<br>(0.02083)   </td><td>0.00310<br>(0.02152)   </td></tr>
<tr><td>month=3 # hour=15   </td><td>-0.22004***<br>(0.02203)   </td><td>0.00000<br>(0.02251)   </td><td>-0.22075***<br>(0.02205)   </td><td>0.00000<br>(0.02254)   </td><td>-0.22036***<br>(0.02203)   </td><td>0.00315<br>(0.02279)   </td></tr>
<tr><td>month=4 # hour=11   </td><td>0.00773<br>(0.02092)   </td><td>0.00000<br>(0.02128)   </td><td>0.00393<br>(0.02091)   </td><td>0.00000<br>(0.02136)   </td><td>0.00602<br>(0.02089)   </td><td>0.00395<br>(0.02138)   </td></tr>
<tr><td>month=4 # hour=12   </td><td>-0.07375***<br>(0.02143)   </td><td>0.00000<br>(0.02174)   </td><td>-0.07825***<br>(0.02139)   </td><td>0.00000<br>(0.02180)   </td><td>-0.07578***<br>(0.02138)   </td><td>0.00402<br>(0.02182)   </td></tr>
<tr><td>month=4 # hour=13   </td><td>-0.11091***<br>(0.02151)   </td><td>0.00000<br>(0.02186)   </td><td>-0.11552***<br>(0.02147)   </td><td>0.00000<br>(0.02192)   </td><td>-0.11298***<br>(0.02146)   </td><td>0.00406<br>(0.02193)   </td></tr>
<tr><td>month=4 # hour=14   </td><td>-0.19457***<br>(0.02186)   </td><td>0.00000<br>(0.02227)   </td><td>-0.19955***<br>(0.02183)   </td><td>0.00000<br>(0.02233)   </td><td>-0.19681***<br>(0.02181)   </td><td>0.00412<br>(0.02231)   </td></tr>
<tr><td>month=4 # hour=15   </td><td>-0.27508***<br>(0.02210)   </td><td>0.00000<br>(0.02259)   </td><td>-0.28012***<br>(0.02210)   </td><td>0.00000<br>(0.02266)   </td><td>-0.27735***<br>(0.02207)   </td><td>0.00419<br>(0.02259)   </td></tr>
<tr><td>month=5 # hour=11   </td><td>0.15657***<br>(0.03650)   </td><td>0.00000<br>(0.03278)   </td><td>0.17085***<br>(0.03878)   </td><td>0.00000<br>(0.03518)   </td><td>0.16300***<br>(0.03739)   </td><td>0.00473<br>(0.03380)   </td></tr>
<tr><td>month=5 # hour=12   </td><td>0.07619**<br>(0.03693)   </td><td>0.00000<br>(0.03369)   </td><td>0.08967**<br>(0.03921)   </td><td>0.00000<br>(0.03608)   </td><td>0.08225**<br>(0.03784)   </td><td>0.00485<br>(0.03464)   </td></tr>
<tr><td>month=5 # hour=13   </td><td>0.03186<br>(0.03772)   </td><td>0.00000<br>(0.03474)   </td><td>0.04454<br>(0.04008)   </td><td>0.00000<br>(0.03734)   </td><td>0.03756<br>(0.03868)   </td><td>0.00493<br>(0.03570)   </td></tr>
<tr><td>month=5 # hour=14   </td><td>-0.05934<br>(0.03765)   </td><td>0.00000<br>(0.03484)   </td><td>-0.04716<br>(0.04007)   </td><td>0.00000<br>(0.03746)   </td><td>-0.05386<br>(0.03864)   </td><td>0.00491<br>(0.03582)   </td></tr>
<tr><td>month=5 # hour=15   </td><td>-0.13268***<br>(0.03810)   </td><td>0.00000<br>(0.03539)   </td><td>-0.12078***<br>(0.04054)   </td><td>0.00000<br>(0.03800)   </td><td>-0.12733***<br>(0.03910)   </td><td>0.00498<br>(0.03639)   </td></tr>
<tr><td>month=6 # hour=11   </td><td>0.12214***<br>(0.03814)   </td><td>0.00000<br>(0.03596)   </td><td>0.13354***<br>(0.04043)   </td><td>0.00000<br>(0.03845)   </td><td>0.12727***<br>(0.03908)   </td><td>0.00904<br>(0.03700)   </td></tr>
<tr><td>month=6 # hour=12   </td><td>0.04115<br>(0.03824)   </td><td>0.00000<br>(0.03631)   </td><td>0.05196<br>(0.04051)   </td><td>0.00000<br>(0.03877)   </td><td>0.04601<br>(0.03918)   </td><td>0.00912<br>(0.03733)   </td></tr>
<tr><td>month=6 # hour=13   </td><td>0.00479<br>(0.03807)   </td><td>0.00000<br>(0.03634)   </td><td>0.01514<br>(0.04038)   </td><td>0.00000<br>(0.03877)   </td><td>0.00945<br>(0.03904)   </td><td>0.00911<br>(0.03738)   </td></tr>
<tr><td>month=6 # hour=14   </td><td>-0.08913**<br>(0.03771)   </td><td>0.00000<br>(0.03626)   </td><td>-0.07951**<br>(0.04001)   </td><td>0.00000<br>(0.03870)   </td><td>-0.08480**<br>(0.03868)   </td><td>0.00906<br>(0.03728)   </td></tr>
<tr><td>month=6 # hour=15   </td><td>-0.17070***<br>(0.03787)   </td><td>0.00000<br>(0.03647)   </td><td>-0.16139***<br>(0.04017)   </td><td>0.00000<br>(0.03892)   </td><td>-0.16651***<br>(0.03884)   </td><td>0.00912<br>(0.03747)   </td></tr>
<tr><td>month=7 # hour=11   </td><td>0.00892<br>(0.04144)   </td><td>0.00000<br>(0.04087)   </td><td>0.01643<br>(0.04379)   </td><td>0.00000<br>(0.04333)   </td><td>0.01230<br>(0.04245)   </td><td>0.00969<br>(0.04168)   </td></tr>
<tr><td>month=7 # hour=12   </td><td>-0.05459<br>(0.04182)   </td><td>0.00000<br>(0.04136)   </td><td>-0.04753<br>(0.04413)   </td><td>0.00000<br>(0.04380)   </td><td>-0.05142<br>(0.04282)   </td><td>0.00968<br>(0.04214)   </td></tr>
<tr><td>month=7 # hour=13   </td><td>-0.10157**<br>(0.04139)   </td><td>0.00000<br>(0.04111)   </td><td>-0.09492**<br>(0.04373)   </td><td>0.00000<br>(0.04354)   </td><td>-0.09858**<br>(0.04240)   </td><td>0.00971<br>(0.04196)   </td></tr>
<tr><td>month=7 # hour=14   </td><td>-0.17786***<br>(0.04132)   </td><td>0.00000<br>(0.04118)   </td><td>-0.17175***<br>(0.04369)   </td><td>0.00000<br>(0.04362)   </td><td>-0.17511***<br>(0.04235)   </td><td>0.00971<br>(0.04206)   </td></tr>
<tr><td>month=7 # hour=15   </td><td>-0.22672***<br>(0.04139)   </td><td>0.00000<br>(0.04110)   </td><td>-0.22017***<br>(0.04360)   </td><td>0.00000<br>(0.04346)   </td><td>-0.22377***<br>(0.04234)   </td><td>0.00975<br>(0.04181)   </td></tr>
<tr><td>month=8 # hour=11   </td><td>0.04308<br>(0.04302)   </td><td>0.00000<br>(0.04290)   </td><td>0.04919<br>(0.04520)   </td><td>0.00000<br>(0.04529)   </td><td>0.04583<br>(0.04397)   </td><td>0.00939<br>(0.04359)   </td></tr>
<tr><td>month=8 # hour=12   </td><td>-0.02810<br>(0.04317)   </td><td>0.00000<br>(0.04313)   </td><td>-0.02234<br>(0.04536)   </td><td>0.00000<br>(0.04550)   </td><td>-0.02551<br>(0.04412)   </td><td>0.00945<br>(0.04383)   </td></tr>
<tr><td>month=8 # hour=13   </td><td>-0.06953<br>(0.04303)   </td><td>0.00000<br>(0.04309)   </td><td>-0.06420<br>(0.04523)   </td><td>0.00000<br>(0.04544)   </td><td>-0.06713<br>(0.04399)   </td><td>0.00946<br>(0.04381)   </td></tr>
<tr><td>month=8 # hour=14   </td><td>-0.15396***<br>(0.04310)   </td><td>0.00000<br>(0.04324)   </td><td>-0.14904***<br>(0.04530)   </td><td>0.00000<br>(0.04558)   </td><td>-0.15175***<br>(0.04406)   </td><td>0.00946<br>(0.04395)   </td></tr>
<tr><td>month=8 # hour=15   </td><td>-0.22787***<br>(0.04491)   </td><td>0.00000<br>(0.04513)   </td><td>-0.22324***<br>(0.04700)   </td><td>0.00000<br>(0.04739)   </td><td>-0.22579***<br>(0.04582)   </td><td>0.00950<br>(0.04574)   </td></tr>
<tr><td>month=9 # hour=11   </td><td>-0.00391<br>(0.04452)   </td><td>0.00000<br>(0.04519)   </td><td>-0.00221<br>(0.04679)   </td><td>0.00000<br>(0.04755)   </td><td>-0.00314<br>(0.04552)   </td><td>0.00998<br>(0.04586)   </td></tr>
<tr><td>month=9 # hour=12   </td><td>-0.08544*<br>(0.04466)   </td><td>0.00000<br>(0.04540)   </td><td>-0.08435*<br>(0.04693)   </td><td>0.00000<br>(0.04774)   </td><td>-0.08495*<br>(0.04566)   </td><td>0.01001<br>(0.04607)   </td></tr>
<tr><td>month=9 # hour=13   </td><td>-0.12778***<br>(0.04449)   </td><td>0.00000<br>(0.04528)   </td><td>-0.12720***<br>(0.04676)   </td><td>0.00000<br>(0.04760)   </td><td>-0.12752***<br>(0.04549)   </td><td>0.01006<br>(0.04593)   </td></tr>
<tr><td>month=9 # hour=14   </td><td>-0.21905***<br>(0.04444)   </td><td>0.00000<br>(0.04526)   </td><td>-0.21890***<br>(0.04672)   </td><td>0.00000<br>(0.04759)   </td><td>-0.21898***<br>(0.04544)   </td><td>0.01007<br>(0.04590)   </td></tr>
<tr><td>month=9 # hour=15   </td><td>-0.29254***<br>(0.04483)   </td><td>0.00000<br>(0.04566)   </td><td>-0.29238***<br>(0.04710)   </td><td>0.00000<br>(0.04797)   </td><td>-0.29247***<br>(0.04582)   </td><td>0.01006<br>(0.04626)   </td></tr>
<tr><td>month=10 # hour=11  </td><td>0.33735***<br>(0.02237)   </td><td>-0.00000<br>(0.02168)   </td><td>0.34472***<br>(0.02284)   </td><td>-0.00000<br>(0.02220)   </td><td>0.34066***<br>(0.02252)   </td><td>-0.00327<br>(0.02211)   </td></tr>
<tr><td>month=10 # hour=12  </td><td>0.27414***<br>(0.02288)   </td><td>-0.00000<br>(0.02237)   </td><td>0.28108***<br>(0.02339)   </td><td>-0.00000<br>(0.02287)   </td><td>0.27726***<br>(0.02305)   </td><td>-0.00313<br>(0.02274)   </td></tr>
<tr><td>month=10 # hour=13  </td><td>0.23653***<br>(0.02301)   </td><td>-0.00000<br>(0.02259)   </td><td>0.24316***<br>(0.02350)   </td><td>-0.00000<br>(0.02308)   </td><td>0.23952***<br>(0.02318)   </td><td>-0.00292<br>(0.02296)   </td></tr>
<tr><td>month=10 # hour=14  </td><td>0.15374***<br>(0.02346)   </td><td>-0.00000<br>(0.02316)   </td><td>0.16003***<br>(0.02394)   </td><td>-0.00000<br>(0.02364)   </td><td>0.15657***<br>(0.02363)   </td><td>-0.00283<br>(0.02350)   </td></tr>
<tr><td>month=10 # hour=15  </td><td>0.08350***<br>(0.02254)   </td><td>-0.00000<br>(0.02211)   </td><td>0.08982***<br>(0.02295)   </td><td>-0.00000<br>(0.02257)   </td><td>0.08634***<br>(0.02268)   </td><td>-0.00278<br>(0.02248)   </td></tr>
<tr><td>month=11 # hour=11  </td><td>0.33347***<br>(0.01932)   </td><td>-0.00000<br>(0.01915)   </td><td>0.33748***<br>(0.01973)   </td><td>-0.00000<br>(0.01955)   </td><td>0.33528***<br>(0.01948)   </td><td>-0.00223<br>(0.01941)   </td></tr>
<tr><td>month=11 # hour=12  </td><td>0.25260***<br>(0.01939)   </td><td>-0.00000<br>(0.01930)   </td><td>0.25633***<br>(0.01978)   </td><td>-0.00000<br>(0.01969)   </td><td>0.25428***<br>(0.01955)   </td><td>-0.00222<br>(0.01956)   </td></tr>
<tr><td>month=11 # hour=13  </td><td>0.20946***<br>(0.01944)   </td><td>-0.00000<br>(0.01939)   </td><td>0.21313***<br>(0.01983)   </td><td>-0.00000<br>(0.01978)   </td><td>0.21111***<br>(0.01959)   </td><td>-0.00208<br>(0.01966)   </td></tr>
<tr><td>month=11 # hour=14  </td><td>0.12463***<br>(0.01929)   </td><td>-0.00000<br>(0.01935)   </td><td>0.12816***<br>(0.01967)   </td><td>-0.00000<br>(0.01974)   </td><td>0.12622***<br>(0.01944)   </td><td>-0.00197<br>(0.01963)   </td></tr>
<tr><td>month=11 # hour=15  </td><td>0.06595***<br>(0.01926)   </td><td>-0.00000<br>(0.01909)   </td><td>0.06956***<br>(0.01950)   </td><td>-0.00000<br>(0.01943)   </td><td>0.06758***<br>(0.01935)   </td><td>-0.00183<br>(0.01941)   </td></tr>
<tr><td>month=12 # hour=11  </td><td>0.26331***<br>(0.01474)   </td><td>-0.00000<br>(0.01501)   </td><td>0.26397***<br>(0.01485)   </td><td>-0.00000<br>(0.01511)   </td><td>0.26361***<br>(0.01478)   </td><td>-0.00011<br>(0.01512)   </td></tr>
<tr><td>month=12 # hour=12  </td><td>0.19328***<br>(0.01680)   </td><td>0.00000<br>(0.01710)   </td><td>0.19372***<br>(0.01688)   </td><td>0.00000<br>(0.01720)   </td><td>0.19348***<br>(0.01684)   </td><td>-0.00005<br>(0.01724)   </td></tr>
<tr><td>month=12 # hour=13  </td><td>0.14465***<br>(0.01687)   </td><td>0.00000<br>(0.01718)   </td><td>0.14483***<br>(0.01695)   </td><td>0.00000<br>(0.01726)   </td><td>0.14473***<br>(0.01690)   </td><td>-0.00005<br>(0.01731)   </td></tr>
<tr><td>month=12 # hour=14  </td><td>0.05046***<br>(0.01558)   </td><td>0.00000<br>(0.01587)   </td><td>0.05038***<br>(0.01565)   </td><td>0.00000<br>(0.01595)   </td><td>0.05042***<br>(0.01561)   </td><td>-0.00002<br>(0.01593)   </td></tr>
<tr><td>month=12 # hour=15  </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td><td>0.00000<br>(.)   </td></tr>
<tr><td>Wind power prognosis same region</td><td>        <br>   </td><td>        <br>   </td><td>        <br>   </td><td>        <br>   </td><td>        <br>   </td><td>-0.00476**<br>(0.00227)   </td></tr>
<tr><td>Wind power prognosis other region</td><td>        <br>   </td><td>        <br>   </td><td>        <br>   </td><td>        <br>   </td><td>        <br>   </td><td>0.01682**<br>(0.00799)   </td></tr>
<tr><td>_cons               </td><td>0.12849<br>(0.87835)   </td><td>0.00000<br>(0.89297)   </td><td>0.21407<br>(0.89081)   </td><td>0.00004<br>(0.90788)   </td><td>0.16699<br>(0.88359)   </td><td>-0.03642<br>(0.89778)   </td></tr>
<tr><td>n*R&sup2            </td><td>               </td><td>               </td><td>               </td><td>               </td><td>               </td><td>        5.87   </td></tr>
<tr><td>p-val               </td><td>               </td><td>               </td><td>               </td><td>               </td><td>               </td><td>        0.02   </td></tr>
<tr><td>Adj. R&sup2         </td><td>        0.99   </td><td>       -0.04   </td><td>        0.99   </td><td>       -0.04   </td><td>        0.99   </td><td>       -0.04   </td></tr>
<tr><td>Observations        </td><td>       3,675   </td><td>       3,675   </td><td>       3,675   </td><td>       3,675   </td><td>       3,675   </td><td>       3,675   </td></tr>
</table>Robust standard errors are in parentheses. * p<0.10, ** p<0.05, *** p<0.01.<br>Baseline: Each hour on Fridays.</html>