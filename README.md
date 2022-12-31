# Ribbon and Bump Chart <br><br/>


### Dashboard
<p align="center">
<img width="650em" src="https://github.com/Power-BI-Solutions/Ribbon-and-Bump-Chart/blob/main/bump_%26_ribbon_chart.gif" align = "center"/>
</p>
<br><br/>

### Data Source
- Financials sample available in Power BI Desktop


### Custom Measures

```dax
Sales Rank = RANKX(ALLSELECTED(financials[Country]),CALCULATE(SUM(financials[ Sales])))
``` 

<br><br/>

### Model

<p align="center">
<img width="650em" src="https://github.com/Power-BI-Solutions/Ribbon-and-Bump-Chart/blob/main/bump_%26_ribbon_data.png" align = "center"/>
</p>
<br><br/>

### Acknowledgements
Source: [WoW Power BI](https://www.workout-wednesday.com/2021-week-11-power-bi-can-you-turn-a-ribbon-chart-into-a-bump-chart/) (Workout Wednesday)

