#### filter couldn't narrow the Types
// Create this helper function
function isNotNullOrUndefined<T extends Object>(input: null | undefined | T): input is T {
    return input != null;
}
// This actually determines that result is of type (string|number)[]
let result = ["", 3,null, undefined].filter(isNotNullOrUndefined);

#### check type
use format isNot... is easier
