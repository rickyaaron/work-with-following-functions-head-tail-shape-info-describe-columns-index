# working-with-following-functions-head-tail-shape-info-describe-columns-index

import pandas as pd

data={"Name":["alice","bob","charlie","david","eve"],

"Age":[14,15,16,17,18],

"City":["hyd","ben","kol","che","mum"]}

df=pd.DataFrame(data)

print(df)

print("1st five \n",df.head())

print("2nd five \n",df.tail(),)

print("information\n",df.info())

print("describe\n",df.describe())

print("shape\n",df.shape)

print("columnsn",df.columns)

print("index\n",df.index)

O/P:

1st five:

Name Age City

0 alice 14 hyd

1 bob 15 ben

2 charlie 16 kol

3 david 17 che

4 eve 18 mum

2nd five:

Name Age City

0 alice 14 hyd

1 bob 15 ben

2 charlie 16 kol

3 david 17 che

4 eve 18 mum

<class 'pandas.core.frame.DataFrame'>

RangeIndex: 5 entries, 0 to 4

Data columns (total 3 columns):

# Column Non-Null Count Dtype

--- ------ -------------- -----

0 Name 5 non-null object

1 Age 5 non-null int64

2 City 5 non-null object

dtypes: int64(1), object(2)

memory usage: 252.0+ bytes

information:

None

describe:

Age

count 5.000000

mean 16.000000

std 1.581139

min 14.000000

25% 15.000000

50% 16.000000

75% 17.000000

max 18.000000

shape:

(5, 3)

columns:

Index(['Name', 'Age', 'City'], dtype='object')

index:

RangeIndex(start=0, stop=5, step=1)# work-with-following-functions-head-tail-shape-info-describe-columns-index
