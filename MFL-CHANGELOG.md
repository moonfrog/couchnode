
v304
basic problem stays that bucket connection is unstable.
# bucket reconnect ensures the previous connection is closed. this was causing issues, as reconnect always saw an existing connection and failed again.
