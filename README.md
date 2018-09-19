public void sendNotification(View view) {
 Intent intent = new Intent(Intent.ACTION_VIEW,
                Uri.parse("https://tutorbagus10.blogspot.com/"));
        PendingIntent pendingIntent = PendingIntent.getActivity(this, 0, intent, 0);
       
