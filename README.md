Create file named .env, it should contain PORT, MONGO_URL, JWT

To run program, "npm start"

To get program ready, "npm install"

These are the APIs you fetch from

Login API ("/api/qrcode/user/login")

Registration API ("/api/qrcode/user/register")

ChangePassword API ("/api/qrcode/user/changepassword")

QRCode Generation API ("/api/qrcode/generate")

View All generated QRcode API ("/api/qrcode/user/qrCode/")

VIEW JUST ONE GENERATED QRcode API ("/api/qrcode/user/qrCode/:id")

Logout API ("/api/qrcode/user/logout"), the logout will be like this, "<a href="/api/qrcode/user/logout">Logout</a>

The public folder is where the frontend will be