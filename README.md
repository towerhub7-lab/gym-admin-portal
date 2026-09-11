# Get In Fit Enterprise - Admin Portal

A comprehensive admin portal for managing gym operations, trainer scheduling, and client bookings.

## Features

- **Admin Authentication**: Secure login system with password management
- **Trainer Management**: Add, view, and manage trainers
- **Permanent Shift Management**: Set fixed shift timings for each trainer
- **Client Master List**: Maintain a centralized list of all clients
- **Slot Booking System**: Interactive slot booking with 30-minute intervals
- **Availability Dashboard**: Real-time overview of trainer availability and client bookings
- **Detailed Client Mapping**: View all client assignments across time slots
- **Excel Export**: Export detailed booking reports with a single click

## Default Credentials

- **Username**: `shazzy`
- **Password**: `shazzy@123`

## How to Use

1. Open `index.html` in a web browser
2. Login with the default credentials
3. Add trainers and set their permanent shift timings
4. Create a master client list
5. Use the slot booking system to assign clients to trainers
6. View dashboards for real-time insights
7. Export to Excel for reporting

## Features in Detail

### Trainers Panel
- Add new trainers
- View all trainers
- Delete trainers from the system

### Permanent Shift Management
- Select a trainer
- Set start and end times
- Save shifts that apply every working day

### Client Management
- Build and maintain a master client list
- Quick access to all registered clients
- Easy client deletion if needed

### Slot Booking
- Select a trainer to view their available slots
- 30-minute slot intervals based on shift times
- Add clients to empty, partially filled, or full slots
- Remove clients from booked slots
- Color-coded slot status:
  - **Green**: Empty slots (0 clients)
  - **Yellow**: Partially filled (1-2 clients)
  - **Red**: Full slots (3 clients)

### Dashboards
- **Availability Dashboard**: Shows empty slots, client count, and trainer status
- **Detailed Client Mapping**: Lists all booked sessions with assigned clients

### Settings
- Change admin password
- Reset to default password if needed

## Technical Stack

- **Frontend**: HTML5, Tailwind CSS, Font Awesome Icons
- **Storage**: Browser LocalStorage
- **Export**: SheetJS (XLSX.js)
- **Framework**: Vanilla JavaScript (No dependencies required)

## Browser Compatibility

- Chrome/Chromium
- Firefox
- Safari
- Edge

## Notes

- All data is stored locally in the browser's LocalStorage
- Data persists between sessions on the same browser
- Excel exports include only booked slots for the current day

## License

MIT License