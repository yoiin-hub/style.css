*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Inter,Arial,sans-serif;
}

body{
    background:#0B1220;
    color:#F8FAFC;
}

.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:25px 8%;
}

.logo{
    font-size:28px;
    font-weight:700;
    color:#22C55E;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}

nav a:hover{
    color:#22C55E;
}

.cta-btn,
.hero-btn{
    background:#22C55E;
    color:white;
    border:none;
    padding:14px 26px;
    border-radius:50px;
    cursor:pointer;
    font-weight:600;
}

.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:80px 8%;
    gap:60px;
}

.hero-text{
    flex:1;
}

.hero-text h1{
    font-size:56px;
    line-height:1.2;
    margin-bottom:25px;
}

.hero-text p{
    color:#94A3B8;
    font-size:18px;
    margin-bottom:30px;
}

.hero-image{
    flex:1;
    display:flex;
    justify-content:center;
}

.chat-card{
    background:#111827;
    border:1px solid #1E293B;
    border-radius:20px;
    padding:30px;
    max-width:420px;
    width:100%;
    box-shadow:0 20px 40px rgba(0,0,0,.35);
}

.chat-header{
    display:flex;
    justify-content:space-between;
    margin-bottom:20px;
    font-weight:bold;
}

.status{
    color:#22C55E;
    font-size:14px;
}

.message{
    padding:14px;
    border-radius:12px;
    margin-bottom:15px;
}

.customer{
    background:#1E293B;
}

.flow{
    background:#16213E;
}

.product-card{
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:#0F172A;
    border:1px solid #334155;
    padding:14px;
    border-radius:12px;
    margin:10px 0;
}

.product-card:hover{
    border-color:#22C55E;
}
