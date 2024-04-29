# art-rsv
RSV parser and serializer for Arturo

## Usage

Add this to your Arturo code:
```red
rsv: import.lean "rsv"!
```

### `_VERSION :version`

Current version of the library.

### `encode rows :block`

Encode block containing block of strings or `null` into RSV.

### `decode data :string`

Decode a string into block containing block of strings or `null`.
