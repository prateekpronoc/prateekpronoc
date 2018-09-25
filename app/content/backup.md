<section class="section" style="margin-bottom: 30px;">
                <div class="section-inner">
                    <h2 class="heading">My GitHub</h2>
                    <div class="panel panel-default">
                        <div class="panel-heading">
                            <div style="display:inline; padding: 9px 0 0; width: 35px; height: 35px;color: #495961;"><i class="fa fa-github fa-3x"></i></div>
                            <div style="display: inline-block;margin: 0 auto;padding: 6px 10px 5px;color:#495961;font-size: 20px;"> <a class="" ng-href="{{vm.gitProfile.html_url}}" target="_blank">Prateek Srivastava</a>
                                <p>
                                    <a class="" ng-href="{{vm.gitProfile.html_url}}" target="_blank">{{vm.gitProfile.login}}</a>
                                </p>
                            </div>
                            <div style="display: inline;float: right;margin-right: 10px; padding-right: 20px;">
                                <a class="" href="https://github.com/caseyscarborough" target="_blank">
                                    <img style="max-width: 60px;height: 67px;" ng-src="{{vm.gitProfile.avatar_url}}" alt="..." class="img-thumbnail">
                                </a>
                            </div>
                        </div>
                        <div class="panel-body tab-pane" >
                            <div style="clear: both;padding: 10px 0;width: 100%;border-bottom: 1px solid #ddd;" ng-repeat="feed in vm.gitFeeds">
                                <!-- <div class="gha-activity-icon"><span><i class="fa fa-circle-o"></i></span></div> -->
                                <div><span><i class="fa fa-circle-o"></i></span>
                                    <a class="" ng-href="{{feed.link}}" target="_blank">{{feed.contentSnippet}}</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>