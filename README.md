<div class="modal fade login-modal-sm in" tabindex="-1" role="dialog" aria-labelledby="" style="display: block;">
    <div class="vertical-alignment-helper">
    <div class="modal-dialog modal-sm vertical-align-center" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <img src="http://static.ph.gameclub.com/Crossfire/images/home/popup_close.png">
                </button>
                <img src="http://static.ph.gameclub.com/Crossfire/images/home/popup_memberlogin.png">
            </div>
            <div class="modal-body">
                <input class="form-control" name="user_id" id="user_id" type="text" placeholder="ID" style="margin-bottom: 10px!important;" onkeypress="if(event.keyCode==13) loginFrmCk();">
                <input class="form-control" name="user_pw" id="user_pw" type="password" placeholder="Password" onkeypress="if(event.keyCode==13) loginFrmCk();">

                <div class="link-container">
                    <div>
                        <a href="javascript:void(0);" onclick="goIdFind();">
                            Forgot Password
                        </a>
                    </div>
                    <div style="float: right;">
                        <a href="javascript:void(0);" onclick="gnbOpenJoin();">
                            Register
                        </a>
                    </div>
                </div>

                <a href="javascript:void(0);" onclick="loginFrmCk();">
                    <img class="imageHover" src="http://static.ph.gameclub.com/Crossfire/images/home/popup_login_off.png" style="margin-bottom: 10px;">
                </a>

                <hr>

                <a href="javascript:void(0);" onclick="gnbOpenBill();">
                    <img class="imageHover" src="http://static.ph.gameclub.com/Crossfire/images/home/popup_addecoin_off.png" style="margin-bottom: 12px;">
                </a>

                <div>
                    <img class="imageHover" src="http://static.ph.gameclub.com/Crossfire/images/home/popup_needhelp.png">
                </div>

                <a href="https://gameclubph.zendesk.com/hc/en-us" target="_blank">
                    <img class="imageHover" src="http://static.ph.gameclub.com/Crossfire/images/home/popup_support_off.png" style="margin-top: 12px;">
                </a>
            </div>
        </div>
    </div>
    </div>
</div>
