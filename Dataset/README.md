# Train Dataset
1. Train dataset have nearly 1 millions records of 1115 stores across 9 features.
2. The target value for this exercise is the Sales column
3. The sales dataset has no missing data.
4. Understanding features
  - Id: transaction ID (combination of Store and date) 
  - Store: unique store Id
  - Sales: sales/day, this is the **target variable** 
  - Customers: number of customers on a given day
  - Open: Boolean to say whether a store is open or closed (0 = closed, 1 = open)
  - Promo: describes if store is running a promo on that day or not
  - StateHoliday: indicate which state holiday (a = public holiday, b = Easter holiday, c = Christmas, 0 = None)
  - SchoolHoliday: indicates if the (Store, Date) was affected by the closure of public schools

# Store Dataset
1. Store dataset has 1115 stores records across 10 features
2. To connect store and train data the Primary key is the Store column
3. The store dataset has missing data 
4. Understanding features
  - StoreType: categorical variable to indicate type of store (a, b, c, d)
  - Assortment: describes an assortment level: a = basic, b = extra, c = extended
  - CompetitionDistance (meters): distance to closest competitor store
  - CompetitionOpenSince [Month/Year]: provides an estimate of the date when competition was open
  - Promo2: Promo2 is a continuing and consecutive promotion for some stores (0 = store is not participating, 1 = store is participating)
  - Promo2Since [Year/Week]: date when the store started participating in Promo2
  - PromoInterval: describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov"     means each round starts in February, May, August, November of any given year for that store.

! [Dataset Correlation Matrix](https://github.com/aeshna25/Future-Daily-Sales-/blob/main/Images/datasetcorr.png)


