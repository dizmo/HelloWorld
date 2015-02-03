function showFront() {
    dizmo.setAttribute('state/front', true);
}

function showBack() {
    // this function will enable the settings button
}

dizmo.onShowBack(function() {
    // this function will be called when state/front is set to false
    dizmo.showBack();
});

dizmo.onShowFront(function() {
    // this function will be called when state/back is set to false
    dizmo.showFront();
});

document.addEventListener('dizmoready', function() {
    DizmoElements('.done-btn').on('click',function({
        showFront();
    });
});
