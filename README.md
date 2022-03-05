# surfs_up

## Overview

The purpose of this analysis is to analyze ttemperature data in Oahu during the months of June and December. This will help W.Avy to determine if the surf and ice crea shop business is sustainable year round.

## Results

Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

- The average temperature decreases by ≈4 degrees in December compated to the average June temperature. 
- The minimum temperature for December is 8 degrees lower than June.
- The max temperature is 85 degrees for June and 83 degrees for December. 

**June Temperature Summary**

![image](https://user-images.githubusercontent.com/91445591/156895963-1556f818-330d-4340-a42a-d5e12bc63cfd.png)

**December Temperature Summary**

![image](https://user-images.githubusercontent.com/91445591/156895983-f1382f46-7c86-401a-b59e-1d9ff2a92e1f.png)

## Summary

- At face value, it appears June and December temperature does not have a significant difference variance which implies the ice cream shop business may be sustainable year round. However, if we plot a histogram for the June and December temperatures, we can see that June has a bellcurve but the december data is a little more random. The Mid-70 temperatures have a significantly higher count than the rest of the temperature ranges.  

**June Temperature Histogram**

```
june_temps_df.plot.hist(bins=20)
plt.tight_layout()
```

![image](https://user-images.githubusercontent.com/91445591/156896415-b4639a94-6f12-404d-9bbb-0ae785a33a01.png)

**December Temperature Histogram**

```
dec_temps_df.plot.hist(bins=20)
plt.tight_layout()
```

![image](https://user-images.githubusercontent.com/91445591/156896424-2b1221ec-ba0e-4632-ad41-eb008376c1e9.png)
