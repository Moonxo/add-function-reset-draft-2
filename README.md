# add-function-reset-draft-2
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
