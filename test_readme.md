componentDidMount() {
    let query=this.props.location.search
    const types = query.split('?edit=')
    if(types[1]==="1"){
      let anchorElement = document.getElementById("newcourseContentMD");
      if(anchorElement){
        this.scrollToAnchor("newcourseContentMD");
      }
    }

  }


def update_file
    interactor = Gitea::UpdateFileInteractor.call(current_user, params.merge(identifier: @project.identifier))
    if interactor.success?
      @file = interactor.result
      create_new_pr(params)
      render_result(1, "更新成功")
    else
      render_error(interactor.error)
    end
  end
  
  dasdfasdf
  as
  dfasd
