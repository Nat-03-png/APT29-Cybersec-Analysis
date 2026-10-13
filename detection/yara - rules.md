# explanation











rule powershell_usage
{
   strings:
       $ps = "powershell"

   condition: 
        $ps
}
