# 方針
 - 40755より大きい数で，三角数，五角数，六角数を満たすように40755以上の数をbrute forceする  
 - もし，数学的に解こうとするならば，二次方程式として，各々の倍数を洗い出し，3変数の探索になる  
 - 何にせよ，単位時間当たりの計算速度が求められそう  

# 失敗
 - Core2Quadで4時間回したが結果出ず  

# 方針変更
 - 一番発散速度が早い六角数をgeneratorにして，三角数と五角数のverifyを行うように変更  

# 結果
 - 3秒ほどで結果が出た  