**The repository has been moved to**

https://github.com/sagemath/memory_allocator

# MemoryAllocator
An extension class to allocate memory easily with cython.

This extension class started as part of the [Sage](https://sagemath.org) software.

It provides a single extension class `MemoryAllocator` with `cdef` methods

- `malloc`,
- `calloc`,
- `alloarray`,
- `realloc`,
- `reallocarray`,
- `aligned_malloc`,
- `aligned_calloc`,
- `aligned_allocarray`.

Memory is freed when the instance of `MemoryAllocator` is deallocated.
On failure to allocate the memory, a proper error is raised.
