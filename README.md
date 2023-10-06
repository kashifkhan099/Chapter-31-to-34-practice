# Chapter-31-to-34-practice
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        var date = new Date();
        console.log(date);
    </script>
</body>
</html>

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Question 2</title>
</head>
<body>
    <script>
         var date = new Date();
        var month = date.getMonth();
        var arr = [
        "Jan",
        "Feb",
        "Mar",
        "Apr",
        "May",
        "Jun",
        "Jul",
        "Aug",
        "Sep",
        "Oct",
        "Nov",
        "Dec",
        ];
        console.log(arr[month]);
        // console.log(month);
       
// var day = date.getDay();
// var array = [
//   "Sunday",
//   "Monday",
//   "Tuesday",
//   "Wednesday",
//   "Thursday",
//   "Friday",
//   "Saturday",
// ];
// console.log(array[day]);
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Q3 of chapter 31 to 34</title>
</head>
<body>
    <script>
      const currentDate = new Date();
      const day = currentDate.getDate();

      if (day === 0 || day === 6) {
        console.log("it's  Funday!");
      }
      else{
        console.log("it's not Fun day. its " + currentDate.toLocaleString('en-us', {weekday: 'long'}) + ".");
        
      }


//         var today = new Date();
//   var day = today.getDay();
//   var daylist = ["Sunday","Monday","Tuesday","Wednesday ","Thursday","Friday","Saturday"];
//   console.log("Today is:" + daylist[day] + ".");
//   var hour = today.getHours();
//   var minute = today.getMinutes();
//   var second = today.getSeconds();
//   var prepand = ((hour>= 12), "PM", "AM");
//   hour = ("hour>= 12 hour: - 12, hour");
//   if (day===0 && prepand===' Saturday ') 
//   { 
//   if (day===0 && second===0)
//   { 
//   hour=12;
//   prepand=' Noon';
//   } 
//   else
//   { 
//   alert ("Its FunDay");
//   } 
//   } 
//   if (day===0 && prepand===' Saturday ') 
//   { 
//   if (day===0 && second===0)
//   { 
//   hour=12;
//   prepand=' Midnight';
//   } 
//   else
//   { 
//     alert("ItsFunday");
//   } 
//   } 
// console.log("today : ");
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Question 2</title>
</head>
<body>
    <script>
        const currentDate = new Date();
        const date = currentDate.getDate();
        const message = date < 16 ? "First fifteen days of the month" : "Last days of the month";
        console.log(message);

    </script>
</body>
</html>
