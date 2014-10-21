WS02 README

INSTRUCTIONS:

Run the server: Use new CSV handler by typing 'csv' as your handler_type

Run the client: Use the new csv_printer handler by typing 'csvprint' as your handler_type


IMPLEMENTATION OF CSV SERVER HANDLER:

Module downloaded from internet converts CSV file into JSON
I stringify the JSON and write it to the response


IMPLEMENTATION OF CSV_PRINTER CLIENT HANDLER:

I parse the string back to a JSON object
I loop through the JSON object and then loop through the individual user objects and print out the attributes of the user
objects adjacent to the value of the attributes
