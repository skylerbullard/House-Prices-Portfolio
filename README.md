# House-Prices-Portfolio


# Why Estimate Home Sale Prices?

Focusing on the product, we would want to predict house prices to give a consumer a better idea of what a home would cost. If a consumer knows the prices of a desireable home, this can help financial planning needed to make a purchase. The sale price of a home in this dataset may not match the final purchase price in real life. Predicting home prices will offer a starting price point for the consumer to consider.

This project aims to give a purchaser an estimate of what a home will cost. This project's final product will be a predictive model trained on a set of house features.

A predictive _mean-squared-error_ model will be evaluated on _Root-Mean-Squared-Error(RMSE)_ between the logarithm of _predicted_ value and the logarithm of _observed_ sales price.

# Strategy

_MSE_ is the average of squared error; the square difference between the predicted and actual target variables divided by total amount of data points. _MSE_ is measured in units square of the target.

_RMSE_ is the square root of _MSE_. _RMSE_ is measured in same units as target variable; penalizes larger errors more.

### To discover the data, we will review for

-missing values
-nulls
-duplicates
-target variable significance
-target relationship to features

# Data

### features: redefined in laymen's terms and specificied measuring units

- 'SalePrice': (target) property sale price in dollars. the target variable
- 'MSSubClass': building classification identifying what house used for
- 'MSZoning:' zoning classification
- 'LotFrontage:' feet of street connected to front
- 'LotArea:' lot size in square feet
- 'Street:' type of road access
- 'Alley:' type of road access
- 'LotShape:' general property shape
- 'LandContour:' property flatness
- 'Utilities:' types of
- 'LotConfig:' access to all sides of building
- 'LandSlope:' average slope of property
- 'Neighborhood:' locations within city limits
- 'Condition 1:' proximity to road or railroad
- 'Condition 2:' proximity to both road or railroad
- 'BldgType:' type of dwelling
- 'HouseStyle:' style of dwelling
- 'OverallQual:' material and finish
- 'OverallCond:' condition rating
- 'YearBuilt:' construction date
- 'YearRemodAdd:' remodel date
- 'RoofStyle:' type of roof
- 'RoofMatl:' material of roof
- 'Exterior1st:' house exterior cover type
- 'Exterior2nd:' more than one exterior cover type
- 'MasVnrType:' veneer type
- 'MasVnrArea:' veneer area square feet
- 'ExterQual:' exterior quality
- 'ExterCond:' exterior actual condition
- 'Foundation:' type of
- 'BsmtQual:' basement height
- 'BsmtCond:' basement condition
- 'BsmtExposure:' walkout basement walls
- 'BsmtFinType1:' finished basement quality
- 'BsmtFinSF1:' Type 1 finish square feet
- 'BsmtFinType2:' second finished basement quality
- 'BsmtFinSF2:' Type 2 finish square feet
- 'BsmtUnfSF:' unfinished basement area
- 'TotalBsmtSF:' basement total square feet
- 'Heating:' type of
- 'HeatingQC:' quality and condition
- 'CentralAir:' central air conditioning
- 'Electrical:' electrical system
- '1stFlrSF:' first floor square feet
- '2ndFlrSF:' second floor square feet
- 'LowQualFinSF:' low quality finish square feet
- 'FrLivArea:' above ground floor square feet
- 'BsmtFullBath:' basement full bathroom
- 'BsmtHalfBath:' basement half bathroom
- 'FullBath:' above ground floor full bathroom
- 'HalfBath:' above ground floor half bathroom
- 'Bedroom:' bedroom count, no basement rooms
- 'Kitchen:' kitchen count
- 'KitchenQual:' quality kitchen
- 'TotRmsAbvGrd:' above ground rooms
- 'Functional:' functionality rating
- 'Fireplaces:' fireplace count
- 'FireplaceQu:' quality fireplace
- 'GarageType:' location of
- 'GarageYrBit:' year garage built
- 'GarageFinish:' garage interior finish
- 'GarageCars:' garage capacity
- 'GarageArea:' garage size square feet
- 'GarageQual:' quality of
- 'GarageCond:' condition of
- 'PavedDrive:' driveway paved
- 'WoodDeckSF:' wood deck square feet
- 'OpenPorchSF:' open porch square feet
- 'EnclosedPorch:' enclosed porch square feet
- '3SsnPorch:' three season porch square feet
- 'ScreenPorch:' screen porch square feet
- 'PoolArea:' pool area square feet
- 'PoolQC:' quality pool
- 'Fence:' quality fence
- 'MiscFeature:' miscellaneous feature not found categorized
- 'MiscVal:' dollar value of miscellaneous feature
- 'MoSold:' month sold
- 'SaleType:' type of
- 'SaleCondition:' condition of






