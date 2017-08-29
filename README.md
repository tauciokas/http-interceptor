# Angular JS http interceptor
Angujar JS complete Http interceptor, with 403 (token refresh) and appending of authorization headers to every request.

On 403 error automatically catches previous request, sends token refresh (stores the response in localstorage) and makes the call which returned 403 again. If 403 fails redirects to login page. 


