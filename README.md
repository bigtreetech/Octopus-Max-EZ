### Ocotpus_Max_EZ Pinout table

<table>
   <tr>
   <td>Peripheral</td><td>Function</td><td>Pin name</td><td>Pin No.</td><td>Comment</td></tr>
   <tr>
   <td rowspan="4">Motor-1</td>
   <td>STEP</td><td>PC13</td><td>7</td><td rowspan="40">All the GPIO related to stepper are converted to 5V output to driver (including STEP, DIR, EN, CS/UART, TMC SPI)</td>
   <tr>
   <td>DIR</td><td>PC14</td><td>8</td></tr>
   <tr>
   <td>EN</td><td>PE6</td><td>5</td></tr>
   <tr>
   <td>CS/UART</td><td>PG14</td><td>129</td></tr>
   <tr>
   <td rowspan="4">Motor-2</td>
   <td>STEP</td><td>PE4</td><td>3</td></tr>
   <tr>
   <td>DIR</td><td>PE5</td><td>4</td></tr>
   <tr>
   <td>EN</td><td>PE3</td><td>2</td></tr>
   <tr>
   <td>CS/UART</td><td>PG13</td><td>128</td></tr>
   <tr>
   <td rowspan="4">Motor-3</td>
   <td>STEP</td><td>PE1</td><td>142</td></tr>
   <tr>
   <td>DIR</td><td>PE0</td><td>141</td></tr>
   <tr>
   <td>EN</td><td>PE2</td><td>1</td></tr>
   <tr>
   <td>CS/UART</td><td>PG12</td><td>127</td></tr>
   <tr>
   <td rowspan="4">Motor-4</td>
   <td>STEP</td><td>PB8</td><td>139</td></tr>
   <tr>
   <td>DIR</td><td>PB9</td><td>140</td></tr>
   <tr>
   <td>EN</td><td>PB7</td><td>137</td></tr>
   <tr>
   <td>CS/UART</td><td>PG11</td><td>126</td></tr>
   <tr>
   <td rowspan="4">Motor-5</td>
   <td>STEP</td><td>PB5</td><td>135</td></tr>
   <tr>
   <td>DIR</td><td>PB4</td><td>134</td></tr>
   <tr>
   <td>EN</td><td>PB6</td><td>136</td></tr>
   <tr>
   <td>CS/UART</td><td>PG10</td><td>125</td></tr>
   <tr>
   <td rowspan="4">Motor-6</td>
   <td>STEP</td><td>PG15</td><td>132</td></tr>
   <tr>
   <td>DIR</td><td>PB3</td><td>133</td></tr>
   <tr>
   <td>EN</td><td>PD5</td><td>119</td></tr>
   <tr>
   <td>CS/UART</td><td>PG9</td><td>124</td></tr>
   <tr>
   <td rowspan="4">Motor-7</td>
   <td>STEP</td><td>PD3</td><td>117</td></tr>
   <tr>
   <td>DIR</td><td>PD2</td><td>116</td></tr>
   <tr>
   <td>EN</td><td>PD4</td><td>118</td></tr>
   <tr>
   <td>CS/UART</td><td>PD7</td><td>123</td></tr>
   <tr>
   <td rowspan="4">Motor-8</td>
   <td>STEP</td><td>PA10</td><td>102</td></tr>
   <tr>
   <td>DIR</td><td>PA9</td><td>101</td></tr>
   <tr>
   <td>EN</td><td>PA15</td><td>110</td></tr>
   <tr>
   <td>CS/UART</td><td>PD6</td><td>122</td></tr>
   <tr>
   <td rowspan="4">Motor-9</td>
   <td>STEP</td><td>PA8</td><td>100</td></tr>
   <tr>
   <td>DIR</td><td>PC7</td><td>97</td></tr>
   <tr>
   <td>EN</td><td>PC9</td><td>99</td></tr>
   <tr>
   <td>CS/UART</td><td>PG8</td><td>93</td></tr>
   <tr>
   <td rowspan="4">Motor-10</td>
   <td>STEP</td><td>PG6</td><td>91</td></tr>
   <tr>
   <td>DIR</td><td>PC6</td><td>96</td></tr>
   <tr>
   <td>EN</td><td>PC8</td><td>98</td></tr>
   <tr>
   <td>CS/UART</td><td>PG7</td><td>92</td></tr>
   <tr>
   <td rowspan="3">TMC SPI (spi4)</td>
   <td>MISO</td><td>PE13</td><td>66</td><td rowspan="3">LCD-FPC SPI, Onboard SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI4, and is converted to 5V to TMC driver</td>
   <tr>
   <td>MOSI</td><td>PE14</td><td>67</td></tr>
   <tr>
   <td>SCK</td><td>PE12</td><td>65</td></tr>
   <tr>
   <td rowspan="5">Heater</td>
   <td>E0</td><td>PF6</td><td>18</td><td rowspan="5">is converted to 5V to MOSFET with flyback protection</td>
   <tr>
   <td>E1</td><td>PA0</td><td>34</td></tr>
   <tr>
   <td>E2</td><td>PF9</td><td>21</td></tr>
   <tr>
   <td>E3</td><td>PF7</td><td>19</td></tr>
   <tr>
   <td>HB(heated bed)</td><td>PF5</td><td>15</td></tr>
   <tr><td rowspan="5">Temperature</td>
   <td>TH0</td><td>PB0</td><td>46</td><td rowspan="4">4.7KOhm 0.1% pull up resistor for NTC100K,etc. 2.2KOhm 0.1% pull up resistor for PT1000 by jumper. with thermistor protection circuit</td>
   <tr>
   <td>TH1</td><td>PC5</td><td>45</td></tr>
   <tr>
   <td>TH2</td><td>PC4</td><td>44</td></tr>
   <tr>
   <td>TH3</td><td>PA7</td><td>43</td></tr>
   <tr>
   <td>THB</td><td>PB1</td><td>47</td><td>with thermistor protection circuit</td></tr>
   <tr><td rowspan="6">Endstop</td>
   <td>M1-STOP</td><td>PF0</td><td>10</td><td rowspan="6">Share with M*-DIAG, And high level exceeding 5V are clamped to 5V by diodes</td>
   <tr>
   <td>M2-STOP</td><td>PF2</td><td>12</td></tr>
   <tr>
   <td>M3-STOP</td><td>PF4</td><td>14</td></tr>
   <tr>
   <td>M4-DET</td><td>PF3</td><td>13</td></tr>
   <tr>
   <td>M5-DET</td><td>PF1</td><td>11</td></tr>
   <tr>
   <td>M6-DET</td><td>PC15</td><td>9</td></tr>
   <tr>
   <td rowspan="4">2 wire FAN</td>
   <td>FAN0</td><td>PA6</td><td>42</td><td rowspan="4">is converted to 5V to MOSFET with flyback protection</td>
   <tr>
   <td>FAN1</td><td>PA5</td><td>41</td></tr>
   <tr>
   <td>FAN2</td><td>PA4</td><td>40</td></tr>
   <tr>
   <td>FAN3</td><td>PA3</td><td>37</td></tr>
   <tr>
   <td rowspan="2">4 wire FAN4</td>
   <td>control</td><td>PA1</td><td>35</td><td>is converted to 5V</td></tr>
   <tr>
   <td>tachometer</td><td>PC3</td><td>29</td><td>isolated by optocoupler</td></tr>
   <tr>
   <td rowspan="2">4 wire FAN5</td>
   <td>control</td><td>PF8</td><td>20</td><td>is converted to 5V</td></tr>
   <tr>
   <td>tachometer</td><td>PC1</td><td>27</td><td>isolated by optocoupler</td></tr>
   <tr>
   <td rowspan="2">4 wire FAN6</td>
   <td>control</td><td>PA2</td><td>36</td><td>is converted to 5V</td></tr>
   <tr>
   <td>tachometer</td><td>PC2</td><td>28</td><td>isolated by optocoupler</td></tr>
   <tr>
   <td rowspan="5">Misc</td>
   <td>RGB1(Neopixel/WS2812)</td><td>PE10</td><td>63</td><td rowspan="2">is converted to 5V</td>
   <tr>
   <td>RGB2(Neopixel/WS2812)</td><td>PE9</td><td>60</td></tr>
   <tr>
   <td>PS-ON</td><td>PF13</td><td>53</td></tr>
   <tr>
   <td>PWRDET</td><td>PF12</td><td>50</td></tr>
   <tr>
   <td>OnBoard LED</td><td>PA14</td><td>109</td></tr>
   <tr>
   <td rowspan="2">BLTouch</td>
   <td>SERVOS</td><td>PB14</td><td>75</td><td></td></tr>
   <tr>
   <td>PROBE</td><td>PB15</td><td>76</td><td></td></tr>
   <tr>
   <td rowspan="1">Proximity switch</td>
   <td>PROBE</td><td>PF11</td><td>49</td><td>isolated by optocoupler, PNP or NPN can be selected by jumper</td></tr>
   <tr>
   <td rowspan="2">FWS(hall_filament_width_sensor)</td>
   <td>adc1</td><td>PC0</td><td>26</td><td></td></tr>
   <tr>
   <td>adc2</td><td>PF10</td><td>22</td><td></td></tr>
   <tr>
   <td rowspan="2">Onboard EEPROM(24C32)</td>
   <td>SCL2</td><td>PB10</td><td>69</td><td></td></tr>
   <tr>
   <td>SDA2</td><td>PB11</td><td>70</td><td></td></tr>
   <tr>
   <td rowspan="2">FDCAN1</td>
   <td>RX</td><td>PD0</td><td>114</td><td></td></tr>
   <tr>
   <td>TX</td><td>PD1</td><td>115</td><td></td></tr>
   <tr>
   <td rowspan="2">TFT UART3</td>
   <td>RX</td><td>PD9</td><td>78</td><td></td></tr>
   <tr>
   <td>TX</td><td>PD8</td><td>77</td><td></td></tr>
   <tr>
   <tr><td rowspan="2">USB-Device</td>
   <td>OTG_FS_DM</td><td>PA11</td><td>103</td><td></td></tr>
   <tr>
   <td>OTG_FS_DP</td><td>PA12</td><td>104</td><td></td></tr>
   <tr>
   <tr><td rowspan="18">LCD-FPC(EXP1 + EXP2)</td>
   <td>5V</td><td>5V</td><td></td><td>EXP1_10</td></tr>
   <tr>
   <td>GND</td><td>GND</td><td></td><td>EXP1_9</td></tr>
   <tr>
   <td>LCD_D7</td><td>PE15</td><td>68</td><td>EXP1_8</td></tr>
   <tr>
   <td>LCD_D6</td><td>PD10</td><td>79</td><td>EXP1_7</td></tr>
   <tr>
   <td>LCD_D5</td><td>PD11</td><td>80</td><td>EXP1_6</td></tr>
   <tr>
   <td>LCD_D4</td><td>PD12</td><td>81</td><td>EXP1_5</td></tr>
   <tr>
   <td>LCD_RS</td><td>PD13</td><td>82</td><td>EXP1_4</td></tr>
   <tr>
   <td>LCD_EN</td><td>PD14</td><td>85</td><td>EXP1_3</td></tr>
   <tr>
   <td>BTN_ENC</td><td>PD15</td><td>86</td><td>EXP1_2</td></tr>
   <tr>
   <td>BEEPER</td><td>PG2</td><td>87</td><td>EXP1_1</td></tr>
   <tr>
   <td>RESET</td><td>RESET</td><td>25</td><td>EXP2_8</td></tr>
   <tr>
   <td>SD_DETECT</td><td>PG3</td><td>88</td><td>EXP2_7</td></tr>
   <tr>
   <td>MOSI</td><td>PE14</td><td>67</td><td>EXP2_6. LCD-FPC SPI, Onboard SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI4, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>BTN_EN2</td><td>PG4</td><td>89</td><td>EXP2_5</td></tr>
   <tr>
   <td>SD_SS</td><td>PE11</td><td>64</td><td>EXP2_4</td></tr>
   <tr>
   <td>BTN_EN1</td><td>PG5</td><td>90</td><td>EXP2_3</td></tr>
   <tr>
   <td>SCK</td><td>PE12</td><td>65</td><td>EXP2_2. LCD-FPC SPI, Onboard SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI4, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td>MISO</td><td>PE13</td><td>66</td><td>EXP2_1. LCD-FPC SPI, Onboard SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI4, and is converted to 5V to TMC driver</td></tr>
   <tr>
   <td rowspan="5">OnboardSD(spi4)</td>
   <td>SD-CS</td><td>PB12</td><td>73</td><td></td></tr>
   <tr>
   <td>SD-DET</td><td>PB13</td><td>74</td><td></td></tr>
   <tr>
   <td>MISO</td><td>PE13</td><td>66</td><td rowspan="3">LCD-FPC SPI, Onboard SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI4, and is converted to 5V to TMC driver</td>
   <tr>
   <td>MOSI</td><td>PE14</td><td>67</td></tr>
   <tr>
   <td>SCK</td><td>PE12</td><td>65</td></tr>
   <tr>
   <td rowspan="4">Expansion SPI pin header(spi4)</td>
   <td>SPI4-CS</td><td>PF14</td><td>54</td><td></td></tr>
   <tr>
   <td>MISO</td><td>PE13</td><td>66</td><td rowspan="3">LCD-FPC SPI, Onboard SD card, expansion SPI pin header and TMC driver SPI, 4 features multiplexing the same hardware SPI4, and is converted to 5V to TMC driver</td>
   <tr>
   <td>MOSI</td><td>PE14</td><td>67</td></tr>
   <tr>
   <td>SCK</td><td>PE12</td><td>65</td></tr>
   <tr>
   <td rowspan="9">WIFI(ESP3D/RRF)</td>
   <td>ESP-RST(espResetPin)</td><td>PB2</td><td>48</td><td></td></tr>
   <tr>
   <td>ESP-IO0(espDataReadyPin)</td><td>PG0</td><td>56</td><td></td></tr>
   <tr>
   <td>ESP-IO4(TfrReadyPin)</td><td>PF15</td><td>55</td><td></td></tr>
   <tr>
   <td>ESP-RX(UART7)</td><td>PE7</td><td>58</td><td></td></tr>
   <tr>
   <td>ESP-TX(UART7)</td><td>PE8</td><td>59</td><td></td></tr>
   <tr>
   <td>ESP-CS</td><td>PG1</td><td>57</td><td></td></tr>
   <tr>
   <td>ESP-MOSI-SPI3</td><td>PC12</td><td>113</td><td></td></tr>
   <tr>
   <td>ESP-MISO-SPI3</td><td>PC11</td><td>112</td><td></td></tr>
   <tr>
   <td>ESP-CLK-SPI3</td><td>PC10</td><td>111</td><td></td></tr>
</table>
