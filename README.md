# mounty-android-test
<b>1-minute Summary</b><br>
Here's a simple summary of this tutorial:<br>

1.<t>User starts the app. He choses either 'View All' data or 'Add New' data.<br>
2.<t>If he choses 'Add New', a new data entry activity is opened, allowing user to input the name, description,selling price,cost price choose image via image picker, then click upload to send data to server.<br>
3.<t>If he chooses 'View All', a new activity is opened. There data is downloaded from Firebase realtime database and firebase storage then bound to the custom recyclerview. We show name, description, date and image.<br>
4.<t>The user can click the RecyclerView CardViews to show a ContextMenu. The ContextMenu contains two options, either 'Show' or 'Delete'. If the user chooses 'Show', a new Details Activity gets opened with the details for that particular user. If he chooses 'Delete', the item is deleted from Firebase, that is the texts are deleted from Firebase realtime database while the image from Firebase Storage.<br>
5.<t>The Custom RecyclerView will be have CardViews with images and text from firebase. The images will be downloaded using Picasso library. When a single cardview is clicked we open a new activity.<br>
6.<t>In that we will order the product and a toast will show to the user that order has been placed
