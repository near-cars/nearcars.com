# nearcars.com
car booking
<!DOCTYPE html>
<html>
<nearcar>
  <title>कार रजिस्ट्रेशन</title>
  <link rel="stylesheet" href="style.css">
</nearcar>
<body>
  <h2>carname</h2>
  <form action="/register" method="POST">
    <input type="text" name="ownerName" placeholder="name" required><br>
    <input type="text" name="mobile" placeholder="mobile number" required><br>
    <input type="text" name="carModel" placeholder="car model" required><br>
    <input type="text" name="carNumber" placeholder="car number" required><br>
    <input type="text" name="location" placeholder="location"><br>
    <button type="submit">register</button>
  </form>
  <a href="/cars">पब्लिक कार लिस्ट देखें</a>
</body>
</html>
