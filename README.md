# HL7Parser-laravel-class
A Laravel PHP class that parses and interprets simple HL7 messages


example of use:

use App\Services\HL7Parser;

$hl7Message = '...'; // Your HL7 message

$parser = new HL7Parser($hl7Message);

// To get the data as a JSON object

$json = $parser->toJSON();

// To get the data as a key-value array

$array = $parser->toArray();
