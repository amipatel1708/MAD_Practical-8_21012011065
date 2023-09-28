# MAD_Practical-8_21012011065

# Study: 

BroadcastReceiver, Service, TextClock, TimePickerDialog, Calendar Class, SimpleDateFormat Class, PendingIntent, AlarmManager, getSystemService() method, sendBroadcast() method, MediaPlayer, startService(), stopService() method, Intent.getStringExtra(), Intent.putStringExtra(), MaterialCardView

# AIM: 

* What is BroadcastReceiver?

 Android BroadcastReceiver is a dormant component of android that listens to system-wide broadcast events or intents. When any of these events occur it brings the application into action by either creating a status bar notification or performing a task.

* Difference between Service and BroadcastReceiver.

 The connection allows both the client and service to exchange messages across the connection. BroadcastReceivers are used to receive events that are announced by other components. For example, activities or other Android components can register for a specific BroadcastReceivers.

 Services are also useful to provide/manage common access to a resource across multiple applications. This is often used for system resources, such as sensors. Broadcast receivers are meant to respond to an intent (usually one sent by a service or a system event), do something, and be done.

* Create an Alarm application by using service & BroadcastReceiver by following below instructions.

* Create MainActivity according to below UI design.

* Create AlarmBroadcastReceiver class

* Create AlarmService Class

* Add android.permission.SCHEDULE_EXACT_ALARM Permission in Manifest file

# OUTPUT:

# Light Theme

![LIGHT_ALARM_1](https://github.com/amipatel1708/MAD_Practical-8_21012011065/assets/139481113/916a3687-20cb-4119-8ea3-4fd31addb09e)

![LIGHT_ALARM_2](https://github.com/amipatel1708/MAD_Practical-8_21012011065/assets/139481113/0a57115e-edc1-4d6e-822b-8d72c944b74f)

![LIGHT_ALARM_3](https://github.com/amipatel1708/MAD_Practical-8_21012011065/assets/139481113/cd50952f-41d7-4c9d-8db9-c4aa2eee3b5d)

# Dark Theme

![DARK_ALARM_1](https://github.com/amipatel1708/MAD_Practical-8_21012011065/assets/139481113/8bf11655-2c91-4853-8283-a00d85aa17cd)

![DARK_ALARM_2](https://github.com/amipatel1708/MAD_Practical-8_21012011065/assets/139481113/17d64264-8d26-4ac3-a75e-b08cc882a0a2)

![DARK_ALARM_3](https://github.com/amipatel1708/MAD_Practical-8_21012011065/assets/139481113/bc15b697-8141-4456-9e36-c4e6b07994f8)
