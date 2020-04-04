# server-alpha
initial server point and for load balance


how to communicate with other servers?

#1

green yellow orange red system
4 levels
green
yellow
orange
red
server-alpha will prioritize lowest level, if no lowest level available, jump to next
if all red, return to user that we are busy
COMMS
alpha -> login     forwarding clients
login -> alpha     updating current status(color)
