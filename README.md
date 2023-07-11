<!-- user route Routes: -->

\*\*user routes
https://digital-cow-server.vercel.app/api/v1/auth/signup create user seller/buyer (post)
https://digital-cow-server.vercel.app/api/v1/admin/create-admin create addmin (post)
https://digital-cow-server.vercel.app/api/v1/users All user get by admin
https://digital-cow-server.vercel.app/api/v1/users/:id get single user
https://digital-cow-server.vercel.app/api/v1/users/:id (PATCH) → Can only be accessed by admin
https://digital-cow-server.vercel.app/api/v1/users/:id (DELETE) → Can only be accessed by admin/

<!-- cow route  -->

\*\* cow routes
https://digital-cow-server.vercel.app/api/v1/cows (POST) → Can only be accessed by seller
https://digital-cow-server.vercel.app/api/v1/cows (GET) → Can only be accessed by buyer,seller & admin
https://digital-cow-server.vercel.app/api/v1/cows/:id (Single GET) → Can only be accessed by buyer,seller & admin
https://digital-cow-server.vercel.app/api/v1/cows/:id (PATCH) → Can only be accessed by the seller of the cow
https://digital-cow-server.vercel.app/api/v1/cows/:id (DELETE) → Can only be accessed by the seller of the cow

<!-- order cow  -->

\*\*OrderRoutes
https://digital-cow-server.vercel.app/api/v1/orders (post)
body:{
cow: id
buyer :id
}
https://digital-cow-server.vercel.app/api/v1/orders (get)

https://digital-cow-server.vercel.app/api/v1/my-profile
