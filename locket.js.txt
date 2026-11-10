var obj = JSON.parse($response.body);
obj.premium = true; 
obj.is_premium = true;
obj.subscription_type = "gold";
obj.status = "active";
obj.expires_date = "2099-12-31T23:59:59Z";
$done({body: JSON.stringify(obj)});
