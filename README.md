# http-interceptor
Angujar JS complete Http interceptor, with 403 (token refresh) and appending of authorization headers to every request.

On 403 error automatically catches previous request, sends token refresh and makes the call again which returned 403. If 403 fails redirects to login page. 


