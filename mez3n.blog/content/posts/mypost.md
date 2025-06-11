+++
title = 'post'
date = 2025-06-11T16:42:17+03:00
+++

This is some C code 






```C
#if __POSIX_VISIBLE >= 202405
/* The Issue 8 standard adds pthread_cond_clockwait() */
int pthread_cond_clockwait(pthread_cond_t *__restrict,
                   pthread_mutex_t *__restrict, clockid_t,
				   const struct timespec *__restrict);
#endif /* __POSIX_VISIBLE >= 202405 */
```