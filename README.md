The attached Python (Colab) notebook allows to simulate the BigQuery usage of on-demand vs editions. 

Note: The notebook is setup to simulate a 100 slots commit. The results are an estimate 

> * BigQuery scales reservations by multiples of 100 until it has reached the number of slots needed to execute the jobs, or it reaches the maximum number of slots available to the reservation.

> * The baseline is the minimum number of slots that will always be allocated to the reservation, and you will always be charged for them

> * A capacity commitment is a purchase of a fixed amount of BigQuery compute capacity for some minimum duration of time. Capacity commitments are optional for reservations created with an edition, but can save on costs for steady-state workloads.
