
## 1.0 [UNRELEASED]

* Venue Details
* Ticket Pricing & Link
* Feature-ability
* Image attachment
* Ticket price requires a number
* Datetime select defaults noon to 1pm
* Scopes: featured, not_featured, upcoming & current
* Friendly ID based on titles
* Archiving
* Admin screen separates events by their status (TODO: pagination somehow)
* Reasonable validations
* Practical instance methods to check against scopes
* Next & previous navigation on individual event pages.
* has_many :categories, :through => :categorizations, :source => :event_category
* RSS feed of current, upcoming & featured events
* Basic Facebook & Twitter sharing interface