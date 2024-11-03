---
Date: 
tags:
  - daily
Created Date: <%tp.file.creation_date("DD/MM/YYYY HH:mm:ss")%>
Modified Date: <%tp.file.last_modified_date("DD/MM/YYYY HH:mm:ss")%>
---
Temperature : <%tp.web.request("https://api.open-meteo.com/v1/forecast?latitude=-6.2548&longitude=106.7621&daily=temperature_2m_max,temperature_2m_min,uv_index_max,rain_sum,wind_speed_10m_max&timezone=Asia%2FBangkok&forecast_days=1", "daily.temperature_2m_max.0")%><%tp.web.request("https://api.open-meteo.com/v1/forecast?latitude=-6.2548&longitude=106.7621&daily=temperature_2m_max,temperature_2m_min,uv_index_max,rain_sum,wind_speed_10m_max&timezone=Asia%2FBangkok&forecast_days=1", "daily_units.temperature_2m_max")%> | UV Index : <%tp.web.request("https://api.open-meteo.com/v1/forecast?latitude=-6.2548&longitude=106.7621&daily=temperature_2m_max,temperature_2m_min,uv_index_max,rain_sum,wind_speed_10m_max&timezone=Asia%2FBangkok&forecast_days=1", "daily.uv_index_max.0")%> | Wind Speed : <%tp.web.request("https://api.open-meteo.com/v1/forecast?latitude=-6.2548&longitude=106.7621&daily=temperature_2m_max,temperature_2m_min,uv_index_max,rain_sum,wind_speed_10m_max&timezone=Asia%2FBangkok&forecast_days=1", "daily.wind_speed_10m_max.0")%><%tp.web.request("https://api.open-meteo.com/v1/forecast?latitude=-6.2548&longitude=106.7621&daily=temperature_2m_max,temperature_2m_min,uv_index_max,rain_sum,wind_speed_10m_max&timezone=Asia%2FBangkok&forecast_days=1", "daily_units.wind_speed_10m_max")%>

[[01 - Notes/Daily/<%tp.date.yesterday("YYYY-MM-DD",tp.file.title)%>|Yesterday]] | [[01 - Notes/Daily/<%tp.date.tomorrow("YYYY-MM-DD",tp.file.title)%>|Tomorrow]]

