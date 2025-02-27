# Adding asset

To add a new asset, go to the **Entities** section > **Assets**, and then select the **`+`** icon > **Add new asset**. Then enter the asset name and create the corresponding asset profile.

| Name          | Asset profile  |
| :----------   | :---------     |
| `Office B`    | office         |

# Adding attributes

To add a new attribute, select the Office B, go to the **Attributes** tab, and select the **`+`** icon. Enter the correspoding key, select the value type, and enter the value itself:

| Key            | Value type     | Value                       |
| :----------    | :---------     | :---------------------------| 
| `address`      | String         | 641 Lexington Ave, New York |
| `floor`        | Integer        | 4                           |
| `email`        | String         | office.b@mail.test          |
| `phone`        | String         | +1 121 666 5522             |
| `officeManager`| String         | Millie Brown                |

# Adding devices

To bulk provision devices:
- Go to **Devices**, select the **`+`** icon > **Import device**.
- Attach your CSV file, select the delimiter, and map the data between the columns of the uploaded file and the data types on the platform.
  
Here's the [CSV file](resources/devices_b.csv) we use in this tutorial. 
