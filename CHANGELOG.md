//for show what you want to show " view result " if you make it public on your github
${project.name === 'yun-yueduqi' ? ` 
                <div div class="button-group">
                    <a href="https://tanaderizcky.github.io/yun-yueduqi/index.html" target="_blank" class="btn btn-small">
                        🌐 View Result
                    </a> 
                    <a href="${project.html_url}" target="_blank" class="btn btn-small" style="background: #6c757d;">
                        📂 View Code
                    </a> //while here to show the code
                </div>
            ` : ` // a separation for what you want to add " view result "
                <a href="${project.html_url}" target="_blank" class="btn btn-small">
                    📂 View Code
                </a> 
