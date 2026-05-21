# API Tests — Postman Basic Requests

## GET — All Users

**URL:** https://jsonplaceholder.typicode.com/users  
**Method:** GET  
**Expected Status Code:** 200  
**Actual Status Code:** 200  
**Result:** Returned 10 users in JSON format  
**Status:** Passed

---

## GET — Single User

**URL:** https://jsonplaceholder.typicode.com/users/1  
**Method:** GET  
**Expected Status Code:** 200  
**Actual Status Code:** 200  
**Result:** Returned only the user with ID 1  
**Status:** Passed

---

## POST — Create Post

**URL:** https://jsonplaceholder.typicode.com/posts  
**Method:** POST  

**Body:**
```json
{
  "title": "meu primeiro post",
  "body": "testando o método POST",
  "userId": 1
}
```

**Expected Status Code:** 201  
**Actual Status Code:** 201  
**Result:** API returned the created object with auto-generated ID 101  
**Status:** Passed

---

## DELETE — Remove Post

**URL:** https://jsonplaceholder.typicode.com/posts/1  
**Method:** DELETE  
**Expected Status Code:** 200  
**Actual Status Code:** 200  
**Result:** API returned an empty object `{}` confirming successful deletion  
**Status:** Passed

---

## DELETE — Remove Post Without ID

**URL:** https://jsonplaceholder.typicode.com/posts/  
**Method:** DELETE  
**Expected Status Code:** 404  
**Actual Status Code:** 404  
**Result:** API returned `404 Not Found` because the endpoint requires a valid post ID  
**Status:** Passed
