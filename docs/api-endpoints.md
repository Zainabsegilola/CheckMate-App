# Authentication 
POST /api/auth/register 
POST /api/auth/login 

# goal and Onboarding 
POST /api/goals 
GET /api/goals/me 

# Pairing 
GET /api/pair-invites/{token} 
POST /api/pair-invites/{token}/accept 
GET /api/pairs/me 


# Daily Proof Submission 
POST /api/proofs 
GET /api/proofs/today 


# Streak and Penalty Processing 
POST /api/jobs/daily-penalties 

# Transactions and Dashboard 
GET /api/transactions
GET /api/dashboard 

# Notifications 
GET /api/notifications 
PUT /api/notifications/{id}/read 
