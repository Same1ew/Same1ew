t = TrackingNumber.new("MYSTERY_TRACKING_NUMBER")
# => #<TrackingNumber::Unknown MYSTERY_TRACKING_NUMBER>
t.valid? #=> false

t = TrackingNumber.new("1Z879E930346834440")
# => #<TrackingNumber::UPS 1Z879E930346834440>
t.valid? #=> true
