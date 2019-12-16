# Task 2
Create a view called 'overview' for each HOBO. Try to solve this task without intermediate views (remind the <span style="color: blue;">UNION</span>...). Refer to the table below for the necessary information. The table is descibing the desired **columns**. The view should have one row for each HOBO:

|  attribute  |    value    |
|-------------|-------------|
|   HOBO id   |  *hobo id*  |
|  raw data   |  _count() of associated data_  |
|  checked data  |  _count() of associated quality checked data_  |
|  hobos within 2km 2019  | _count other hobos within a distance of 2km in 2020_  |
|  hobos within 2km  | _count other hobos within a distance of 2km in all years_  |
|  used in 2020  |  yes/no  |
|  used in 2018  |  yes/no  |
|  used in 2017  |  yes/no  |

the last three coulmns can either contain the string 'yes' or 'no' or just a boolean value. They should indicate if the same hobo id was used ba a student during the last three years.