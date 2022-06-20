# utils
C++ header which contains definition of usefull types and improved containers from STD library.

## Types

**Basic types:**
 * `i16`, `u16`, `i32`, `u32`, `i64`, `u64` - unsigned and signed integer types of different sizes
 * `str` - improved `std::string` which supports transformation methods (`to_lower()`, `to_upper()` and etc.)
 * `byte` - alias for `std::byte`
 * `size` - alias for `std::size_t`

**Collections:**
 * `block_storage<N>` - linked list which stores fixed size blocks of binary data
 * `hset<T>` - alias for `std::unordered_set<T>`
 * `set<T>` - alias for `std::set<T>`
 * `map<K, V>` - alias for `std::map<K, V>`
 * `hmap<K, V>` - alias for `std::unordered_map<K, V>`
