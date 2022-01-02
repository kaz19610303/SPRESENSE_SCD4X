# SPRESENSE_CO2 SCD4X
CO2,temperature and humidity sensores bord for SPRESENSE.

**CO2センサー 「SCD4x」**  
サイズの壁を打ち破るCO2センシング  
SCD4xは、他に類をみないコストパフォーマンス比率を実現したセンシリオンの次世代小型CO2センサーです。  
テープ＆リールパッケージとSMD組立て処理との組み合わせによって、SCD4xは大量生産のアプリケーションに対応します。  
  
このセンサーは光音響センシング原理とセンシリオンの特許技術、 PASens® および CMOSens®技術により、比類ない小型サイズと高性能を両立させています。  
SMD互換性と小さなフットプリントによって、コスト効率およびスペース効率をもたらし、お客様のニーズに合わせた自由な設計を可能にします。  
クラス最高の温湿度センサーの内蔵によって、優れたオンチップ信号補正と追加の湿度および温度データの出力が可能になります。  
広範囲な電源電圧（2.4 V～5.5 V）、外部からの負荷に対する堅牢性、調整可能な消費電力により、SCD4xは様々なお客様のニーズに対応します。  
  
**特徴**  
■サイズ: 10.1 x 10.1 x 6.5 ㎣  
■取り付けタイプ: SMD  
■インターフェース: I2C  
■電源電圧範囲: 2.4 ～ 5.5 V  
■消費電力:  
　17 mA (測定間隔= 5秒)  
　0.5 mA (測定間隔= 5分)  
■オンチップ 温湿度補償:　あり  
■出力範囲: 0 ppm ～ 40,000 ppm  
  
**アプリケーション**  
■デマンド制御換気  
■室内空気質モニタリング  
■CO2換気警報器  
■IoT / スマートホーム  
■農業・グリーン住宅  
■産業用  
  
センサー仕様  
|名称|精度|指定測定範囲|低消費電力測定機能|
|:----|:----|:----|:----|
|SCD40|±(50 ppm +読み取り値の5%)|400 ppm ～ 2'000 ppm|なし|
|SCD41|±(40 ppm +読み取り値の5%)|400 ppm ～ 5'000 ppm|あり|
|SCD42|±75 ppm	400 ppm ～ 1'000 ppm|なし|
  
CPUボード    
[Sony SPRESENSE](https://developer.sony.com/ja/develop/spresense/)  
  
プロラム開発環境    
[Spresense Arduino](https://developer.sony.com/develop/spresense/docs/arduino_set_up_ja.html)  
  
参考資料  
[Datasheet CO2 Sensors SCD40 and SCD41] 
(https://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/9.5_CO2/Sensirion_CO2_Sensors_SCD40_SCD41_Datasheet.pdf)  
  
[Handling Instructions CO2 Sensor SCD4x]
(https://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/9.5_CO2/Sensirion_CO2_Sensors_SCD4x_handling_instructions.pdf)  
  
[Design-In Guide CO2 Sensor SCD4x]
(https://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/9.5_CO2/Sensirion_CO2_Sensors_SCD4x_design-in_guide.pdf)
  
[Sensirion I2C SCD4x Arduino Library]
(https://github.com/Sensirion/arduino-i2c-scd4x)
