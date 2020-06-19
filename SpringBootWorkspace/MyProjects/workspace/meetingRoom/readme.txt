List of assumptions

1.only one company having lots of building.
2.while booking meeting time clash logic is not considered.
3.each meetingid has unique number
4.each floorid has unique number

PostMan Url

List Available Rooms: Lists all available meeting rooms (with id, name etc), given the meeting room type building name, and floor (optional)
POST-> http://localhost:8080/listMeetingRoom

Make Booking: Books the meeting room having the specified id. It returns success/failure. If successful, returns a booking reference id.
POST -> http://localhost:8080/bookMeeting?meetingId=2

Cancel Booking: Removes booking for specified reference id.
Delete->http://localhost:8080/cancelMeeting?meetingId=2
