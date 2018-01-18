This version uses a fork of sameersbn's postgresql to add:

* max_connections=300 to all masters and slaves.
* random_page_cost=1 to all masters and slaves.
* shared_buffers=2500MB to all masters and slaves.
* hot_standby_feedback=on to all slaves.
