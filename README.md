# Hacking-for-Change

Explanation of the equations used (Equations go from left to right, so Equation 1 is to the left of Equation 2

Equation 1 involves the variable "txtInput" where the user inputs their kwd (kilowatts per day), multiplied by 30 (for days in a month) further multiplied by the quotient of 14,920lbs (an estimated average of a US household’s carbon footprint)1  and 957kwh (The monthly average of kwh)1  to obtain the user’s estimated carbon footprint, variable “CoalEffect”.

Equation 2 focuses on how much your carbon footprint is reduced when switching to solar panels. We use the variable “CoalEffect” from the last equation and subtract 250 (The monthly reduction rate with 1kw solar panels)[1] to get the reduced carbon footprint, variable “SolarEffect”

Equation 3 finds your average electric bill using the variable "txtInput" and multiplying it by 30 to find the monthly kwh rate. This is once again multiplied 13.19 (The average cost per kwh)[2] then divided by 100 (As seen by this equation here)[3]. We end up with the total average bill cost based on the user’s input; the total is also known as the variable “CoalCost”

Equation 4 provides your monthly electric bill if you have a typical 1kw solar panel. The original information came from a 6kw panel and how much it saves yearly; we divided that number by 6 to get the average savings of 1kw annually, which was 250$[4]. We further divided this by 12 (years) to gain a monthly average of $20.83. We then use the “CoalCost” variable and subtract 20.83 from it to gain the variable, “SolarCost”

Equation 5 calculates how much coal you use daily, using the variable “txtInput” we divide that value by .038 (The daily amount of kwh produced per pound of coal)[5] to give us “CoalTime” measured in pounds

Equation 6 calculates how much energy is produced by a 1kw solar panel, using variable “txtInput” we divide it by 2.33 (The yearly output of a 1kw solar panel divided by 365)[6] to get our variable answer, “SolarTime”.

1: https://aresolar.com/the-benefits-of-going-solar-helping-the-environment-while-saving-you-money/

2: https://www.electricchoice.com/electricity-prices-by-state/

3: https://www.apge.com/average-electric-bill

4. https://www.solarreviews.com/blog/what-is-the-average-solar-savings-for-a-residential-solar-installation-in-the-us#:~:text=The%20average%206%20kW%20solar,local%20city%20and%20state%20incentives.

5. https://www.eia.gov/tools/faqs/faq.php?id=667&t=2#:~:text=Coal%E2%80%940.91%20kWh%20per%20pound

6. http://www.theecoexperts.com/solar-panel-output/



