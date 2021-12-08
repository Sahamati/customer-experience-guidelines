# AA Profile Lifecycle

### AA handle issued

|                                              |                                                                           |
| -------------------------------------------- | ------------------------------------------------------------------------- |
| Event triggering a notification              | AA handle issued                                                          |
| Mandatory (M) / Optional (O)                 | M                                                                         |
| Sender                                       | AA                                                                        |
| Receiver                                     | Customer                                                                  |
| Customer notification, based on response to: | Issuance of a handle on successful registration by a customer with the AA |
| Notification Content                         | —                                                                         |

### AA handle modified

|                                              |                                                              |
| -------------------------------------------- | ------------------------------------------------------------ |
| Event triggering a notification              | AA handle modified                                           |
| Mandatory (M) / Optional (O)                 | M                                                            |
| Sender                                       | AA                                                           |
| Receiver                                     | Customer                                                     |
| Customer notification, based on response to: | Modification of a handle by the customer on the AA interface |
| Notification Content                         | —                                                            |



## Tabular checklist

| Event triggering a notification | Mandatory (M) / Optional (O) | Sender | Receiver | Customer notification, based on response to                                                                                         |
| ------------------------------- | ---------------------------- | ------ | -------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| AA handle issued                | M                            | AA     | Customer | Issuance of a handle on successful registration by a customer with the AA                                                           |
| AA handle modified              | M                            | AA     | Customer | Modification of handle by the customer on the AA interface                                                                          |
| User Details modified           | O                            | AA     | Customer | Modification of details (name, mobile number) by the customer on the AA interface                                                   |
| Authentication factors modified | M                            | AA     | Customer | Modification of authentication factors stored by the AA (biometric, passphrase, PIN, Password), by the customer on the AA interface |
