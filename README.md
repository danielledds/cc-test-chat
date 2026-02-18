
<!-- NICE CXone (inContact) Chat Embed -->
<script type="text/javascript" src="https://home-c19.incontact.com/inContact/ChatClient/js/embed.min.js"></script>
<script type="text/javascript">
  // Initialize the chat client
  icPatronChat.init({
    serverHost: 'https://home-c19.incontact.com',
    bus_no: 4596165, // your Business Unit number
    poc: 'fc6d6f36-cc00-42f7-9746-321e907f568d', // Point of Contact GUID
    // Optional: pre-chat parameters (see notes below)
    params: [
      { name: 'FirstName', value: 'First' },
      { name: 'LastName', value: 'Last' },
      { name: 'Email', value: 'first.last@company.com' },
      { name: 'Phone', value: '555-555-5555' }
    ]
  });
</script>
