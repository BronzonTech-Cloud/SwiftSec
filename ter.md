ReferenceError: document is not defined
(anonymous function)
file:///home/thechain/Desktop/devops/examples/security/src/App.tsx:32
  30 |
  31 | // Add global event listener for button taps
> 32 | document.addEventListener('click', handleTap);
     | ^  33 |
  34 | return () => {
  35 |   document.removeEventListener('click', handleTap);
View compiled
▶ 4 stack frames were collapsed.
(anonymous function)
file:///home/thechain/Desktop/devops/packages/react/runtime/lib/lifecycle/patch/commit.js:61
  59 |     updateBackgroundRefs(commitTaskId);
  60 |     runDelayedUnmounts(delayedUnmounts);
> 61 |     oldCommit?.(vnode, renderCallbacks);
     | ^  62 |     renderCallbacks.some(wrapper => {
  63 |         try {
  64 |             wrapper[RENDER_CALLBACKS].some((cb) => {
View compiled
(anonymous function)
file:///home/thechain/Desktop/devops/packages/react/runtime/lib/lynx/tt.js:157
  155 |         return;
  156 |     }
> 157 |     commitTask();
      | ^  158 |     globalCommitTaskMap.delete(id);
  159 | });
  160 | break;
View compiled
onLifecycleEventImpl
file:///home/thechain/Desktop/devops/packages/react/runtime/lib/lynx/tt.js:159
  157 |         commitTask();
  158 |         globalCommitTaskMap.delete(id);
> 159 |     });
      | ^  160 |     break;
  161 | }
  162 | case LifecycleConstant.globalEventFromLepus: {
View compiled
