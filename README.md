# Make_workflow_for_creating_videos_based_on_whatsapp_message
This is an automation workflow created using 'Make.com'. It will create a video based on the received message, upload it on YouTube and reply back with the Youtube video link.
It has below components
1) Whatsapp business - To watch for new message
2) Google vertex AI - to create a prompt for video generation
3) Google vertex ai - To genearte video using the prompt
4) Youtube to upload the video
5) Whatsapp to send the thr reply with the video link
6) Excel sheet to store the message, prompt and video link.
