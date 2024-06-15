# 台北捷運時刻表

之前捷運時刻表採用 PDF，將其轉換為自定的 JSON 格式，這裡特點是處理了底線，所以輸出結果中包含了該班車終點站的資訊。

後來有 TDX 平台，所以時刻表可以用 API 方式取得，這裡也轉成跟之前相同的格式。
欲取得原始資料，請至 https://tdx.transportdata.tw/api-service/swagger/basic/268fc230-2e04-471b-a728-a726167c1cfc#/Metro/MetroApi_StationTimeTable_2104

轉換程式的程式碼放在 https://github.com/ericyu/TaipeiMetroTimeTableParser

注意事項：
- 目前沒有處理新北投支線及小碧潭支線。
- 文湖線沒有公佈時刻表。
