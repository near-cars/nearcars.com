<!DOCTYPE html>
<html>
<head>
  <title>कार रजिस्ट्रेशन</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h2>अपनी कार रजिस्टर करें</h2>
  <form action="/register" method="POST">
    <input type="text" name="ownerName" placeholder="नाम" required><br>
    <input type="text" name="mobile" placeholder="मोबाइल नंबर" required><br>
    <input type="text" name="carModel" placeholder="कार मॉडल" required><br>
    <input type="text" name="carNumber" placeholder="कार नंबर" required><br>
    <input type="text" name="location" placeholder="लोकेशन"><br>
    <button type="submit">रजिस्टर करें</button>
  </form>
  <a href="/cars">पब्लिक कार लिस्ट देखें</a>
</body>
</html>
