# Error State [.d.ts]

angular material | formControl `ErrorStateMatcher`

### @[error state link]

```ts
export interface CanUpdateErrorState {
    updateErrorState(): any;
    readonly stateChanges: Subject<void>;
    errorState: boolean;
    errorStateMatcher: ErrorStateMatcher;
}
/** @docs-private */
export interface HasErrorState {
    _parentFormGroup: FormGroupDirective;
    _parentForm: NgForm;
    _defaultErrorStateMatcher: ErrorStateMatcher;
    ngControl: NgControl;
}
/**
 * Mixin to augment a directive with updateErrorState method.
 * For component with `errorState` and need to update `errorState`.
 */
export declare function mixinErrorState<T extends Constructor<HasErrorState>>(base: T): Constructor<CanUpdateErrorState> & T;
```




[error state link]: https://cr.wh-redirect.deepin.cn/plugins/gitiles/vendor-deps/+/ca83fda596dab56bc702a87c16f2dfa344e008b2/@angular/material/typings/core/common-behaviors/error-state.d.ts
