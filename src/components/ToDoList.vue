<template>
  <!--  BEGIN MAIN CONTAINER  -->
  <div id="container" class="main-container">
    <div class="overlay"/>
    <div class="search-overlay"/>

    <!--  BEGIN SIDEBAR  -->
    <div class="sidebar-wrapper sidebar-theme">
      <nav id="sidebar">
        <div class="shadow-bottom"/>

        <ul id="accordionExample" class="list-unstyled menu-categories">
          <li class="menu">
            <a data-toggle="collapse" aria-expanded="false" class="dropdown-toggle">
              <div class="">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-home"
                >
                  <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/>
                  <polyline points="9 22 9 12 15 12 15 22"/>
                </svg>
                <span>Dashboard</span>
              </div>
              <div>
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-chevron-right"
                >
                  <polyline points="9 18 15 12 9 6"/>
                </svg>
              </div>
            </a>
            <ul
                id="dashboard"
                class="collapse submenu list-unstyled"
                data-parent="#accordionExample"
            >
              <li>
                <a href="index-2.html"> Sales </a>
              </li>
              <li>
                <a href="index2.html"> Analytics </a>
              </li>
            </ul>
          </li>

          <li class="menu">
            <a data-toggle="collapse" aria-expanded="true" class="dropdown-toggle">
              <div class="">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-cpu"
                >
                  <rect
                      x="4"
                      y="4"
                      width="16"
                      height="16"
                      rx="2"
                      ry="2"
                  />
                  <rect
                      x="9"
                      y="9"
                      width="6"
                      height="6"
                  />
                  <line
                      x1="9"
                      y1="1"
                      x2="9"
                      y2="4"
                  />
                  <line
                      x1="15"
                      y1="1"
                      x2="15"
                      y2="4"
                  />
                  <line
                      x1="9"
                      y1="20"
                      x2="9"
                      y2="23"
                  />
                  <line
                      x1="15"
                      y1="20"
                      x2="15"
                      y2="23"
                  />
                  <line
                      x1="20"
                      y1="9"
                      x2="23"
                      y2="9"
                  />
                  <line
                      x1="20"
                      y1="14"
                      x2="23"
                      y2="14"
                  />
                  <line
                      x1="1"
                      y1="9"
                      x2="4"
                      y2="9"
                  />
                  <line
                      x1="1"
                      y1="14"
                      x2="4"
                      y2="14"
                  />
                </svg>
                <span>Apps</span>
              </div>
              <div>
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-chevron-right"
                >
                  <polyline points="9 18 15 12 9 6"/>
                </svg>
              </div>
            </a>
            <ul
                id="app"
                class="collapse submenu list-unstyled show"
                data-parent="#accordionExample"
            >
              <li>
                <a href="apps_chat.html"> Chat </a>
              </li>
              <li>
                <a href="apps_mailbox.html"> Mailbox </a>
              </li>
              <li class="active">
                <a href="apps_todoList.html"> Todo List </a>
              </li>
              <li>
                <a href="apps_notes.html"> Notes </a>
              </li>
              <li>
                <a href="apps_scrumboard.html">Scrumboard</a>
              </li>
              <li>
                <a href="apps_contacts.html"> Contacts </a>
              </li>
              <li>
                <a href="apps_invoice.html"> Invoice List </a>
              </li>
              <li>
                <a href="apps_calendar.html"> Calendar </a>
              </li>
            </ul>
          </li>

          <li class="menu">
            <a data-toggle="collapse" aria-expanded="false" class="dropdown-toggle">
              <div class="">
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-box"
                >
                  <path
                      d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"
                  />
                  <polyline points="3.27 6.96 12 12.01 20.73 6.96"/>
                  <line
                      x1="12"
                      y1="22.08"
                      x2="12"
                      y2="12"
                  />
                </svg>
                <span>Components</span>
              </div>
              <div>
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-chevron-right"
                >
                  <polyline points="9 18 15 12 9 6"/>
                </svg>
              </div>
            </a>
            <ul
                id="components"
                class="collapse submenu list-unstyled"
                data-parent="#accordionExample"
            >
              <li>
                <a href="component_tabs.html"> Tabs </a>
              </li>
              <li>
                <a href="component_accordion.html"> Accordions </a>
              </li>
              <li>
                <a href="component_modal.html"> Modals </a>
              </li>
              <li>
                <a href="component_cards.html"> Cards </a>
              </li>
              <li>
                <a href="component_bootstrap_carousel.html">Carousel</a>
              </li>
              <li>
                <a href="component_blockui.html"> Block UI </a>
              </li>
              <li>
                <a href="component_countdown.html"> Countdown </a>
              </li>
              <li>
                <a href="component_counter.html"> Counter </a>
              </li>
              <li>
                <a href="component_sweetalert.html"> Sweet Alerts </a>
              </li>
              <li>
                <a href="component_timeline.html"> Timeline </a>
              </li>
              <li>
                <a href="component_snackbar.html"> Notifications </a>
              </li>
              <li>
                <a href="component_session_timeout.html"> Session Timeout </a>
              </li>
              <li>
                <a href="component_media_object.html"> Media Object </a>
              </li>
              <li>
                <a href="component_list_group.html"> List Group </a>
              </li>
              <li>
                <a href="component_pricing_table.html"> Pricing Tables </a>
              </li>
              <li>
                <a href="component_lightbox.html"> Lightbox </a>
              </li>
            </ul>
          </li>
        </ul>
      </nav>
    </div>
    <!--  END SIDEBAR  -->

    <!--  BEGIN CONTENT AREA  -->
    <div id="content" class="main-content">
      <div class="layout-px-spacing">

        <div class="row layout-top-spacing">
          <div class="col-xl-12 col-lg-12 col-md-12">

            <div class="mail-box-container">
              <div class="mail-overlay"></div>

              <div class="tab-title">
                <div class="row">
                  <div class="col-md-12 col-sm-12 col-12 text-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                         stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                         class="feather feather-clipboard">
                      <path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path>
                      <rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect>
                    </svg>
                    <h5 class="app-title">Todo List</h5>
                  </div>

                  <div class="todoList-sidebar-scroll">
                    <div class="col-md-12 col-sm-12 col-12 mt-4 pl-0">
                      <ul class="nav nav-pills d-block" id="pills-tab" role="tablist">
                        <li class="nav-item">
                          <a class="nav-link list-actions active" id="all-list" data-toggle="pill" href="#pills-inbox"
                             role="tab" aria-selected="true">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                                 class="feather feather-list">
                              <line x1="8" y1="6" x2="21" y2="6"></line>
                              <line x1="8" y1="12" x2="21" y2="12"></line>
                              <line x1="8" y1="18" x2="21" y2="18"></line>
                              <line x1="3" y1="6" x2="3" y2="6"></line>
                              <line x1="3" y1="12" x2="3" y2="12"></line>
                              <line x1="3" y1="18" x2="3" y2="18"></line>
                            </svg>
                            Inbox <span class="todo-badge badge"></span></a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link list-actions" id="todo-task-done" data-toggle="pill" href="#pills-sentmail"
                             role="tab" aria-selected="false">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                                 class="feather feather-thumbs-up">
                              <path
                                  d="M14 9V5a3 3 0 0 0-3-3l-4 9v11h11.28a2 2 0 0 0 2-1.7l1.38-9a2 2 0 0 0-2-2.3zM7 22H4a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h3"></path>
                            </svg>
                            Done <span class="todo-badge badge"></span></a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link list-actions" id="todo-task-important" data-toggle="pill"
                             href="#pills-important" role="tab" aria-selected="false">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                                 class="feather feather-star">
                              <polygon
                                  points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon>
                            </svg>
                            Important <span class="todo-badge badge"></span></a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link list-actions" id="todo-task-trash" data-toggle="pill" href="#pills-trash"
                             role="tab" aria-selected="false">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                                 class="feather feather-trash-2">
                              <polyline points="3 6 5 6 21 6"></polyline>
                              <path
                                  d="M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6m3 0V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"></path>
                              <line x1="10" y1="11" x2="10" y2="17"></line>
                              <line x1="14" y1="11" x2="14" y2="17"></line>
                            </svg>
                            Trash</a>
                        </li>
                      </ul>
                    </div>
                  </div>

                  <a class="btn" id="addTask" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                         stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                         class="feather feather-plus">
                      <line x1="12" y1="5" x2="12" y2="19"></line>
                      <line x1="5" y1="12" x2="19" y2="12"></line>
                    </svg>
                    New Task</a>
                </div>
              </div>

              <div id="todo-inbox" class="accordion todo-inbox">
                <div class="search">
                  <input type="text" class="form-control input-search" placeholder="Search Here...">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                       stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                       class="feather feather-menu mail-menu d-lg-none">
                    <line x1="3" y1="12" x2="21" y2="12"></line>
                    <line x1="3" y1="6" x2="21" y2="6"></line>
                    <line x1="3" y1="18" x2="21" y2="18"></line>
                  </svg>
                </div>

                <div class="todo-box">

                  <div id="ct" class="todo-box-scroll">

                    <div v-for="item in todo" :key="item.id"
                         class="todo-item"
                         :class="item.cssClasses"
                    >
                      <div class="todo-item-inner">
                        <div class="n-chk text-center">
                          <label class="new-control new-checkbox checkbox-primary">
                            <input type="checkbox" class="new-control-input inbox-chkbox">
                            <span class="new-control-indicator"></span>
                          </label>
                        </div>

                        <div class="todo-content">
                          <h5 class="todo-heading" :data-todoHeading="item.heading">{{ item.heading }}</h5>
                          <p class="meta-date">{{ item.date }}</p>
                          <p class="todo-text"
                             :data-todoHtml="'<p>'+ item.text +'</p>'"
                             :data-todoText="item.textAttr">
                            {{ item.text }}
                          </p>
                        </div>

                        <div class="priority-dropdown custom-dropdown-icon">
                          <div class="dropdown p-dropdown">
                            <a class="dropdown-toggle" :class="item.priority" href="#" role="button" id="dropdownMenuLink-1"
                               data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                   fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                   stroke-linejoin="round" class="feather feather-alert-octagon">
                                <polygon
                                    points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon>
                                <line x1="12" y1="8" x2="12" y2="12"></line>
                                <line x1="12" y1="16" x2="12" y2="16"></line>
                              </svg>
                            </a>

                            <div class="dropdown-menu" aria-labelledby="dropdownMenuLink-1">
                              <a class="dropdown-item danger" href="javascript:void(0);">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                     fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                     stroke-linejoin="round" class="feather feather-alert-octagon">
                                  <polygon
                                      points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon>
                                  <line x1="12" y1="8" x2="12" y2="12"></line>
                                  <line x1="12" y1="16" x2="12" y2="16"></line>
                                </svg>
                                High</a>
                              <a class="dropdown-item warning" href="javascript:void(0);">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                     fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                     stroke-linejoin="round" class="feather feather-alert-octagon">
                                  <polygon
                                      points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon>
                                  <line x1="12" y1="8" x2="12" y2="12"></line>
                                  <line x1="12" y1="16" x2="12" y2="16"></line>
                                </svg>
                                Middle</a>
                              <a class="dropdown-item primary" href="javascript:void(0);">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                     fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                     stroke-linejoin="round" class="feather feather-alert-octagon">
                                  <polygon
                                      points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon>
                                  <line x1="12" y1="8" x2="12" y2="12"></line>
                                  <line x1="12" y1="16" x2="12" y2="16"></line>
                                </svg>
                                Low</a>
                            </div>
                          </div>
                        </div>

                        <div class="action-dropdown custom-dropdown-icon">
                          <div class="dropdown">
                            <a class="dropdown-toggle" href="#" role="button" id="dropdownMenuLink-2"
                               data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                   fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                   stroke-linejoin="round" class="feather feather-more-vertical">
                                <circle cx="12" cy="12" r="1"></circle>
                                <circle cx="12" cy="5" r="1"></circle>
                                <circle cx="12" cy="19" r="1"></circle>
                              </svg>
                            </a>

                            <div class="dropdown-menu" aria-labelledby="dropdownMenuLink-2">
                              <a class="edit dropdown-item" href="javascript:void(0);">Edit</a>
                              <a class="important dropdown-item" href="javascript:void(0);">Important</a>
                              <a class="dropdown-item delete" href="javascript:void(0);">Delete</a>
                              <a class="dropdown-item permanent-delete" href="javascript:void(0);">Permanent Delete</a>
                              <a class="dropdown-item revive" href="javascript:void(0);">Revive Task</a>
                            </div>
                          </div>
                        </div>

                      </div>
                    </div>

                  </div>

                  <div class="modal fade" id="todoShowListItem" tabindex="-1" role="dialog" aria-hidden="true">
                    <div class="modal-dialog modal-dialog-centered" role="document">
                      <div class="modal-content">
                        <div class="modal-body">
                          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                               stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                               class="feather feather-x close" data-dismiss="modal">
                            <line x1="18" y1="6" x2="6" y2="18"></line>
                            <line x1="6" y1="6" x2="18" y2="18"></line>
                          </svg>
                          <div class="compose-box">
                            <div class="compose-content">
                              <h5 class="task-heading"></h5>
                              <p class="task-text"></p>
                            </div>
                          </div>
                        </div>
                        <div class="modal-footer">
                          <button class="btn" data-dismiss="modal">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                                 class="feather feather-trash">
                              <polyline points="3 6 5 6 21 6"></polyline>
                              <path
                                  d="M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6m3 0V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"></path>
                            </svg>
                            Close
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

              </div>
            </div>

            <!-- Modal -->
            <div class="modal fade" id="addTaskModal" tabindex="-1" role="dialog" aria-labelledby="addTaskModalTitle"
                 aria-hidden="true">
              <div class="modal-dialog modal-dialog-centered" role="document">
                <div class="modal-content">
                  <div class="modal-body">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                         stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                         class="feather feather-x close" data-dismiss="modal">
                      <line x1="18" y1="6" x2="6" y2="18"></line>
                      <line x1="6" y1="6" x2="18" y2="18"></line>
                    </svg>
                    <div class="compose-box">
                      <div class="compose-content" id="addTaskModalTitle">
                        <h5 class="">Add Task</h5>
                        <form>
                          <div class="row">
                            <div class="col-md-12">
                              <div class="d-flex mail-to mb-4">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                     fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                     stroke-linejoin="round" class="feather feather-edit-3 flaticon-notes">
                                  <path d="M12 20h9"></path>
                                  <path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"></path>
                                </svg>
                                <div class="w-100">
                                  <input id="task" type="text" placeholder="Task" class="form-control" name="task">
                                  <span class="validation-text"></span>
                                </div>
                              </div>
                            </div>
                          </div>

                          <div class="d-flex  mail-subject mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                                 class="feather feather-file-text flaticon-menu-list">
                              <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
                              <polyline points="14 2 14 8 20 8"></polyline>
                              <line x1="16" y1="13" x2="8" y2="13"></line>
                              <line x1="16" y1="17" x2="8" y2="17"></line>
                              <polyline points="10 9 9 9 8 9"></polyline>
                            </svg>
                            <div class="w-100">
                              <div id="taskdescription" class=""></div>
                              <span class="validation-text"></span>
                            </div>
                          </div>

                        </form>
                      </div>
                    </div>
                  </div>
                  <div class="modal-footer">
                    <button class="btn" data-dismiss="modal"><i class="flaticon-cancel-12"></i> Discard</button>
                    <button class="btn add-tsk">Add Task</button>
                    <button class="btn edit-tsk">Save</button>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>

      </div>
      <div class="footer-wrapper">
        <div class="footer-section f-section-1">
          <p class="">Copyright © 2020 <a target="_blank" href="https://designreset.com/">DesignReset</a>, All rights
            reserved.</p>
        </div>
        <div class="footer-section f-section-2">
          <p class="">Coded with
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                 stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                 class="feather feather-heart">
              <path
                  d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path>
            </svg>
          </p>
        </div>
      </div>
    </div>
    <!--  END CONTENT AREA  -->
  </div>
  <!-- END MAIN CONTAINER -->
</template>

<script>
  import $ from "jquery";
  import PerfectScrollbar from "@/assets/plugins/perfect-scrollbar/perfect-scrollbar.min";
  import Quill from "@/assets/plugins/editors/quill/quill";

  export default {
    name: "ToDoList",
    data: function () {
      return {
        todo:[
          {
            id: 0,
            heading: "Meet Lisa to discuss project details",
            date: "Aug, 05 2019",
            text: "Nam consectetur, nunc vitae convallis fermentum, libero urna laoreet felis, sed euismod tellus nulla nec quam. Etiam sit amet erat eu ante euismod lacinia. Cras id pretium tellus. Fusce ac ex eros. Quisque id ipsum diam. Pellentesque elementum eros vel viverra condimentum. Proin at fermentum tortor. Maecenas eu varius eros, quis accumsan lectus. Aliquam erat volutpat. Phasellus nec diam nec dolor eleifend tincidunt vitae sed purus. Sed sed ipsum eu arcu condimentum malesuada non quis risus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque facilisis risus a velit tincidunt aliquam. Donec rutrum lectus in diam pellentesque tempor. Aliquam porttitor velit at massa fermentum, cursus lacinia felis porta.",
            done: false,
            important: false,
            removed: false,
            priority: "primary",
            textAttr: "{\"ops\":[{\"insert\":\"Nam consectetur, nunc vitae convallis fermentum, libero urna laoreet felis, sed euismod tellus nulla nec quam. Etiam sit amet erat eu ante euismod lacinia. Cras id pretium tellus. Fusce ac ex eros. Quisque id ipsum diam. Pellentesque elementum eros vel viverra condimentum. Proin at fermentum tortor. Maecenas eu varius eros, quis accumsan lectus. Aliquam erat volutpat. Phasellus nec diam nec dolor eleifend tincidunt vitae sed purus. Sed sed ipsum eu arcu condimentum malesuada non quis risus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque facilisis risus a velit tincidunt aliquam. Donec rutrum lectus in diam pellentesque tempor. Aliquam porttitor velit at massa fermentum, cursus lacinia felis porta.\\n\"}]}",
            cssClasses: "all-list",
          },
          {
            id: 1,
            heading: "Meet Lisa to discuss project details",
            date: "May, 04 2059",
            text: "Nullam sollicitudin id nisi at mollis. Integer pellentesque enim purus, consectetur accumsan urna rhoncus sit amet. Suspendisse hendrerit ipsum sed porttitor ornare. Sed pharetra turpis sed interdum suscipit. Sed congue hendrerit faucibus. Donec blandit maximus enim sed vestibulum. Duis mollis quis ligula id auctor. Suspendisse potenti. Nulla faucibus dictum ornare. Sed a ullamcorper diam. Nullam gravida laoreet magna vitae condimentum. Ut at imperdiet magna, id interdum neque. Vivamus viverra magna eu ante efficitur porta. Maecenas dolor diam, ullamcorper molestie purus sit amet, lobortis accumsan risus. Nullam id molestie diam. Suspendisse sed dictum urna.",
            done: true,
            important: true,
            removed: false,
            priority: "warning",
            textAttr: "{\"ops\":[{\"insert\":\"Nullam sollicitudin id nisi at mollis. Integer pellentesque enim purus, consectetur accumsan urna rhoncus sit amet. Suspendisse hendrerit ipsum sed porttitor ornare. Sed pharetra turpis sed interdum suscipit. Sed congue hendrerit faucibus. Donec blandit maximus enim sed vestibulum. Duis mollis quis ligula id auctor. Suspendisse potenti. Nulla faucibus dictum ornare. Sed a ullamcorper diam. Nullam gravida laoreet magna vitae condimentum. Ut at imperdiet magna, id interdum neque. Vivamus viverra magna eu ante efficitur porta. Maecenas dolor diam, ullamcorper molestie purus sit amet, lobortis accumsan risus. Nullam id molestie diam. Suspendisse sed dictum urna.\\n\"}]}",
            cssClasses: "all-list todo-task-done todo-task-important"
          },
          {
            id: 2,
            heading: "Meet Lisa to discuss project details",
            date: "May, 04 2059",
            text: "Nunc fringilla euismod odio ut sollicitudin. Morbi vulputate eros in ligula condimentum ullamcorper. Sed in ligula quam. Integer tincidunt mauris est, vitae elementum ipsum viverra ut. Ut vel enim consequat eros pretium ornare a vitae sapien. Nullam quis odio orci. Ut erat elit, posuere sed arcu rhoncus, auctor varius augue. Ut porta odio quis ornare tincidunt. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id lacus pellentesque felis pharetra pulvinar. Pellentesque velit massa, pulvinar et viverra non, vehicula a est. Sed egestas, arcu vestibulum sollicitudin porttitor, quam est varius tellus, nec placerat ipsum justo accumsan leo. Pellentesque fermentum arcu ligula, vel efficitur erat ultricies in. Mauris hendrerit massa a sem dignissim, sed scelerisque tellus rhoncus. Sed molestie vel felis eget maximus. Aenean cursus mauris elit, et finibus orci ultrices vel.",
            done: false,
            important: true,
            removed: false,
            priority: "primary",
            textAttr: "{\"ops\":[{\"insert\":\"Nunc fringilla euismod odio ut sollicitudin. Morbi vulputate eros in ligula condimentum ullamcorper. Sed in ligula quam. Integer tincidunt mauris est, vitae elementum ipsum viverra ut. Ut vel enim consequat eros pretium ornare a vitae sapien. Nullam quis odio orci. Ut erat elit, posuere sed arcu rhoncus, auctor varius augue. Ut porta odio quis ornare tincidunt. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id lacus pellentesque felis pharetra pulvinar. Pellentesque velit massa, pulvinar et viverra non, vehicula a est. Sed egestas, arcu vestibulum sollicitudin porttitor, quam est varius tellus, nec placerat ipsum justo accumsan leo. Pellentesque fermentum arcu ligula, vel efficitur erat ultricies in. Mauris hendrerit massa a sem dignissim, sed scelerisque tellus rhoncus. Sed molestie vel felis eget maximus. Aenean cursus mauris elit, et finibus orci ultrices vel.\\n\"}]}",
            cssClasses: "all-list todo-task-important"
          },
          {
            id: 3,
            heading: "AAAAMeet Lisa to discuss project details",
            date: "May, 04 2059",
            text: "Nunc fringilla euismod odio ut sollicitudin. Morbi vulputate eros in ligula condimentum ullamcorper. Sed in ligula quam. Integer tincidunt mauris est, vitae elementum ipsum viverra ut. Ut vel enim consequat eros pretium ornare a vitae sapien. Nullam quis odio orci. Ut erat elit, posuere sed arcu rhoncus, auctor varius augue. Ut porta odio quis ornare tincidunt. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id lacus pellentesque felis pharetra pulvinar. Pellentesque velit massa, pulvinar et viverra non, vehicula a est. Sed egestas, arcu vestibulum sollicitudin porttitor, quam est varius tellus, nec placerat ipsum justo accumsan leo. Pellentesque fermentum arcu ligula, vel efficitur erat ultricies in. Mauris hendrerit massa a sem dignissim, sed scelerisque tellus rhoncus. Sed molestie vel felis eget maximus. Aenean cursus mauris elit, et finibus orci ultrices vel.",
            done: false,
            important: true,
            removed: true,
            priority: "danger",
            textAttr: "{\"ops\":[{\"insert\":\"Nunc fringilla euismod odio ut sollicitudin. Morbi vulputate eros in ligula condimentum ullamcorper. Sed in ligula quam. Integer tincidunt mauris est, vitae elementum ipsum viverra ut. Ut vel enim consequat eros pretium ornare a vitae sapien. Nullam quis odio orci. Ut erat elit, posuere sed arcu rhoncus, auctor varius augue. Ut porta odio quis ornare tincidunt. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam id lacus pellentesque felis pharetra pulvinar. Pellentesque velit massa, pulvinar et viverra non, vehicula a est. Sed egestas, arcu vestibulum sollicitudin porttitor, quam est varius tellus, nec placerat ipsum justo accumsan leo. Pellentesque fermentum arcu ligula, vel efficitur erat ultricies in. Mauris hendrerit massa a sem dignissim, sed scelerisque tellus rhoncus. Sed molestie vel felis eget maximus. Aenean cursus mauris elit, et finibus orci ultrices vel.\\n\"}]}",
            cssClasses: "todo-task-trash todo-task-important"
          }
        ]
      }
    },
    methods: {},
    mounted() {

      $('.input-search').on('keyup', function () {
        let rex = new RegExp($(this).val(), 'i');
        $('.todo-box .todo-item').hide();
        $('.todo-box .todo-item').filter(function () {
          return rex.test($(this).text());
        }).show();
      });

      new PerfectScrollbar('.task-text', {
        wheelSpeed: .5,
        swipeEasing: !0,
        minScrollbarLength: 40,
        maxScrollbarLength: 300,
        suppressScrollX: true
      });

      function dynamicBadgeNotification(setTodoCategoryCount) {
        let todoCategoryCount = setTodoCategoryCount;

        // Get Parents Div(s)
        let get_ParentsDiv = $('.todo-item');
        console.log(get_ParentsDiv);
        let get_TodoAllListParentsDiv = $('.todo-item.all-list');
        let get_TodoCompletedListParentsDiv = $('.todo-item.todo-task-done');
        let get_TodoImportantListParentsDiv = $('.todo-item.todo-task-important');

        // Get Parents Div(s) Counts
        let get_TodoListElementsCount = get_TodoAllListParentsDiv.length;
        let get_CompletedTaskElementsCount = get_TodoCompletedListParentsDiv.length;
        let get_ImportantTaskElementsCount = get_TodoImportantListParentsDiv.length;

        // Get Badge Div(s)
        let getBadgeTodoAllListDiv = $('#all-list .todo-badge');
        let getBadgeCompletedTaskListDiv = $('#todo-task-done .todo-badge');
        let getBadgeImportantTaskListDiv = $('#todo-task-important .todo-badge');


        if (todoCategoryCount === 'allList') {
          if (get_TodoListElementsCount === 0) {
            getBadgeTodoAllListDiv.text('');
            return;
          }
          if (get_TodoListElementsCount > 9) {
            getBadgeTodoAllListDiv.css({
              padding: '2px 0px',
              height: '25px',
              width: '25px'
            });
          } else if (get_TodoListElementsCount <= 9) {
            getBadgeTodoAllListDiv.removeAttr('style');
          }
          getBadgeTodoAllListDiv.text(get_TodoListElementsCount);
        }
        else if (todoCategoryCount === 'completedList') {
          if (get_CompletedTaskElementsCount === 0) {
            getBadgeCompletedTaskListDiv.text('');
            return;
          }
          if (get_CompletedTaskElementsCount > 9) {
            getBadgeCompletedTaskListDiv.css({
              padding: '2px 0px',
              height: '25px',
              width: '25px'
            });
          } else if (get_CompletedTaskElementsCount <= 9) {
            getBadgeCompletedTaskListDiv.removeAttr('style');
          }
          getBadgeCompletedTaskListDiv.text(get_CompletedTaskElementsCount);
        }
        else if (todoCategoryCount === 'importantList') {
          if (get_ImportantTaskElementsCount === 0) {
            getBadgeImportantTaskListDiv.text('');
            return;
          }
          if (get_ImportantTaskElementsCount > 9) {
            getBadgeImportantTaskListDiv.css({
              padding: '2px 0px',
              height: '25px',
              width: '25px'
            });
          } else if (get_ImportantTaskElementsCount <= 9) {
            getBadgeImportantTaskListDiv.removeAttr('style');
          }
          getBadgeImportantTaskListDiv.text(get_ImportantTaskElementsCount);
        }
      }

      new dynamicBadgeNotification('allList');
      new dynamicBadgeNotification('completedList');
      new dynamicBadgeNotification('importantList');

      /*
        ====================
          Quill Editor
        ====================
      */

      let quill = new Quill('#taskdescription', {
        modules: {
          toolbar: [
            [{header: [1, 2, false]}],
            ['bold', 'italic', 'underline'],
            ['image', 'code-block']
          ]
        },
        placeholder: 'Compose an epic...',
        theme: 'snow'  // or 'bubble'
      });

      $('#addTaskModal').on('hidden.bs.modal', function () {
        // do something...
        $(this)
          .find("input,textarea,select")
          .val('')
          .end();

        quill.deleteText(0, 2000);

        console.log('message added')
      })
      $('.mail-menu').on('click', function () {
        $('.tab-title').addClass('mail-menu-show');
        $('.mail-overlay').addClass('mail-overlay-show');
      })
      $('.mail-overlay').on('click', function () {
        $('.tab-title').removeClass('mail-menu-show');
        $('.mail-overlay').removeClass('mail-overlay-show');
      })
      $('#addTask').on('click', function (event) {
        event.preventDefault();
        $('.add-tsk').show();
        $('.edit-tsk').hide();
        $('#addTaskModal').modal('show');

       new PerfectScrollbar('.todo-box-scroll', {suppressScrollX: true});
      });

      new PerfectScrollbar('.todo-box-scroll', {
        suppressScrollX: true
      });
      new PerfectScrollbar('.todoList-sidebar-scroll', {
        suppressScrollX: true
      });


      function checkCheckbox() {
        $('.todo-item input[type="checkbox"]').click(function () {
          if ($(this).is(":checked")) {
            $(this).parents('.todo-item').addClass('todo-task-done');
          } else if ($(this).is(":not(:checked)")) {
            $(this).parents('.todo-item').removeClass('todo-task-done');
          }
          new dynamicBadgeNotification('completedList');
        });
      }

      function deleteDropdown() {
        $('.action-dropdown .dropdown-menu .delete.dropdown-item').click(function () {
          if (!$(this).parents('.todo-item').hasClass('todo-task-trash')) {

            let getTodoParent = $(this).parents('.todo-item');
            let getTodoClass = getTodoParent.attr('class');

            let getFirstClass = getTodoClass.split(' ')[1];
            let getSecondClass = getTodoClass.split(' ')[2];
            let getThirdClass = getTodoClass.split(' ')[3];

            if (getFirstClass === 'all-list') {
              getTodoParent.removeClass(getFirstClass);
            }
            if (getSecondClass === 'todo-task-done' || getSecondClass === 'todo-task-important') {
              getTodoParent.removeClass(getSecondClass);
            }
            if (getThirdClass === 'todo-task-done' || getThirdClass === 'todo-task-important') {
              getTodoParent.removeClass(getThirdClass);
            }
            $(this).parents('.todo-item').addClass('todo-task-trash');
          } else if ($(this).parents('.todo-item').hasClass('todo-task-trash')) {
            $(this).parents('.todo-item').removeClass('todo-task-trash');
          }
          new dynamicBadgeNotification('allList');
          new dynamicBadgeNotification('completedList');
          new dynamicBadgeNotification('importantList');
        });
      }

      function deletePermanentlyDropdown() {
        $('.action-dropdown .dropdown-menu .permanent-delete.dropdown-item').on('click', function (event) {
          event.preventDefault();
          if ($(this).parents('.todo-item').hasClass('todo-task-trash')) {
            $(this).parents('.todo-item').remove();
          }
        });
      }

      function reviveMailDropdown() {
        $('.action-dropdown .dropdown-menu .revive.dropdown-item').on('click', function (event) {
          event.preventDefault();
          if ($(this).parents('.todo-item').hasClass('todo-task-trash')) {
            let getTodoParent = $(this).parents('.todo-item');
            let getTodoClass = getTodoParent.attr('class');
            let getFirstClass = getTodoClass.split(' ')[1];
            $(this).parents('.todo-item').removeClass(getFirstClass);
            $(this).parents('.todo-item').addClass('all-list');
            $(this).parents('.todo-item').hide();
          }
          new dynamicBadgeNotification('allList');
          new dynamicBadgeNotification('completedList');
          new dynamicBadgeNotification('importantList');
        });
      }

      function importantDropdown() {
        $('.important').click(function () {
          if (!$(this).parents('.todo-item').hasClass('todo-task-important')) {
            $(this).parents('.todo-item').addClass('todo-task-important');
            $(this).html('Back to List');
          } else if ($(this).parents('.todo-item').hasClass('todo-task-important')) {
            $(this).parents('.todo-item').removeClass('todo-task-important');
            $(this).html('Important');
            $(".list-actions#all-list").trigger('click');
          }
          new dynamicBadgeNotification('importantList');
        });
      }

      function priorityDropdown() {
        $('.priority-dropdown .dropdown-menu .dropdown-item').on('click', function () {

          let getClass = $(this).attr('class').split(' ')[1];
          let getDropdownClass = $(this).parents('.p-dropdown').children('.dropdown-toggle').attr('class').split(' ')[1];
          $(this).parents('.p-dropdown').children('.dropdown-toggle').removeClass(getDropdownClass);

          $(this).parents('.p-dropdown').children('.dropdown-toggle').addClass(getClass);
        })
      }

      function editDropdown() {
        $('.action-dropdown .dropdown-menu .edit.dropdown-item').click(function () {

          event.preventDefault();

          let $_outerThis = $(this);

          $('.add-tsk').hide();
          $('.edit-tsk').show();

          let $_taskTitle = $_outerThis.parents('.todo-item').children().find('.todo-heading').attr('data-todoHeading');
          let $_taskText = $_outerThis.parents('.todo-item').children().find('.todo-text').attr('data-todoText');
          let $_taskJson = JSON.parse($_taskText);

          $('#task').val($_taskTitle);
          quill.setContents($_taskJson);

          $('.edit-tsk').off('click').on('click', function () {
            let $_innerThis = $(this);
            console.log("$_innerThis");
            console.log($_innerThis);
            let $_task = document.getElementById('task').value;
            let $_taskDescription = document.getElementById('taskdescription').value;
            console.log("$_taskDescription");
            console.log($_taskDescription);

            let today = new Date();
            let dd = String(today.getDate()).padStart(2, '0');
            let mm = String(today.getMonth()); //January is 0!
            let yyyy = today.getFullYear();
            let monthNames = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];

            today = monthNames[mm] + ', ' + dd + ' ' + yyyy;


            let $_taskDescriptionText = quill.getText();
            let $_taskDescriptionInnerHTML = quill.root.innerHTML;

            let delta = quill.getContents();
            let $_textDelta = JSON.stringify(delta);

            let length = 125;

            let trimmedString = $_taskDescriptionText.length > length ?
              $_taskDescriptionText.substring(0, length - 3) + "..." :
              $_taskDescriptionText;

            $_outerThis.parents('.todo-item').children().find('.todo-heading').html($_task);
            $_outerThis.parents('.todo-item').children().find('.todo-text').html(trimmedString);
            $_outerThis.parents('.todo-item').children().find('.meta-date').html(today);

            let $_taskEditedTitleDataAttr = $_outerThis.parents('.todo-item').children().find('.todo-heading').attr('data-todoHeading', $_task);
            let $_taskEditedTextDataAttr = $_outerThis.parents('.todo-item').children().find('.todo-text').attr('data-todoText', $_textDelta);
            $_taskEditedTextDataAttr = $_outerThis.parents('.todo-item').children().find('.todo-text').attr('data-todoHtml', $_taskDescriptionInnerHTML);

            console.log("$_taskEditedTitleDataAttr");
            console.log($_taskEditedTitleDataAttr);
            console.log("$_taskEditedTextDataAttr");
            console.log($_taskEditedTextDataAttr);


            $('#addTaskModal').modal('hide');
          });
          $('#addTaskModal').modal('show');
        })
      }

      function todoItem() {
        $('.todo-item .todo-content').on('click', function (event) {
          event.preventDefault();

          let $_taskTitle = $(this).find('.todo-heading').attr('data-todoHeading');
          let $todoHtml = $(this).find('.todo-text').attr('data-todoHtml');

          $('.task-heading').text($_taskTitle);
          $('.task-text').html($todoHtml);

          $('#todoShowListItem').modal('show');
        });
      }

      let $btns = $('.list-actions').click(function () {
        if (this.id == 'all-list') {
          let $el = $('.' + this.id).fadeIn();
          $('#ct > div').not($el).hide();
        } else if (this.id == 'todo-task-trash') {
          let $el = $('.' + this.id).fadeIn();
          $('#ct > div').not($el).hide();
        } else {
          let $el = $('.' + this.id).fadeIn();
          $('#ct > div').not($el).hide();
        }
        $btns.removeClass('active');
        $(this).addClass('active');
      })

      checkCheckbox();
      deleteDropdown();
      deletePermanentlyDropdown();
      reviveMailDropdown();
      importantDropdown();
      priorityDropdown();
      editDropdown();
      todoItem();

      $(".add-tsk").click(function () {
        let today = new Date();
        let dd = String(today.getDate()).padStart(2, '0');
        let mm = String(today.getMonth()); //January is 0!
        let yyyy = today.getFullYear();
        let monthNames = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];

        today = monthNames[mm] + ', ' + dd + ' ' + yyyy;
        let $_task = document.getElementById('task').value;

        let $_taskDescriptionText = quill.getText();
        let $_taskDescriptionInnerHTML = quill.root.innerHTML;

        let delta = quill.getContents();
        let $_textDelta = JSON.stringify(delta);

        let $html = '<div class="todo-item all-list">' +
          '<div class="todo-item-inner">' +
          '<div class="n-chk text-center">' +
          '<label class="new-control new-checkbox checkbox-primary">' +
          '<input type="checkbox" class="new-control-input inbox-chkbox">' +
          '<span class="new-control-indicator"></span>' +
          '</label>' +
          '</div>' +

          '<div class="todo-content">' +
          '<h5 class="todo-heading" data-todoHeading="' + $_task + '"> ' + $_task + '</h5>' +
          '<p class="meta-date">' + today + '</p>' +
          "<p class='todo-text' data-todoHtml='" + $_taskDescriptionInnerHTML + "' data-todoText='" + $_textDelta + "'> " + $_taskDescriptionText + "</p>" +
          '</div>' +

          '<div class="priority-dropdown">' +
          '<div class="dropdown p-dropdown">' +
          '<a class="dropdown-toggle primary" href="#" role="button" id="dropdownMenuLink-4" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">' +
          '<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12" y2="16"></line></svg>' +
          '</a>' +

          '<div class="dropdown-menu" aria-labelledby="dropdownMenuLink-4">' +
          '<a class="dropdown-item danger" href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12" y2="16"></line></svg> High</a>' +
          '<a class="dropdown-item warning" href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12" y2="16"></line></svg> Middle</a>' +
          '<a class="dropdown-item primary" href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12" y2="16"></line></svg> Low</a>' +
          '</div>' +
          '</div>' +
          '</div>' +

          '<div class="action-dropdown">' +
          '<div class="dropdown">' +
          '<a class="dropdown-toggle" href="#" role="button" id="dropdownMenuLink-4" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">' +
          '<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-more-vertical"><circle cx="12" cy="12" r="1"></circle><circle cx="12" cy="5" r="1"></circle><circle cx="12" cy="19" r="1"></circle></svg>' +
          '</a>' +

          '<div class="dropdown-menu" aria-labelledby="dropdownMenuLink-4">' +
          '<a class="dropdown-item edit" href="javascript:void(0);">Edit</a>' +
          '<a class="important dropdown-item" href="javascript:void(0);">Important</a>' +
          '<a class="dropdown-item delete" href="javascript:void(0);">Delete</a>' +
          '<a class="dropdown-item permanent-delete" href="javascript:void(0);">Permanent Delete</a>' +
          '<a class="dropdown-item revive" href="javascript:void(0);">Revive Task</a>' +
          '</div>' +
          '</div>' +
          '</div>' +

          '</div>' +
          '</div>';


        $("#ct").prepend($html);
        $('#addTaskModal').modal('hide');
        checkCheckbox();
        deleteDropdown();
        deletePermanentlyDropdown();
        reviveMailDropdown();
        editDropdown();
        priorityDropdown();
        todoItem();
        importantDropdown();
        new dynamicBadgeNotification('allList');
        $(".list-actions#all-list").trigger('click');
      });

      $('.tab-title .nav-pills a.nav-link').on('click', function () {
        $(this).parents('.mail-box-container').find('.tab-title').removeClass('mail-menu-show')
        $(this).parents('.mail-box-container').find('.mail-overlay').removeClass('mail-overlay-show')
      })

// Validation Process

      let $_getValidationField = document.getElementsByClassName('validation-text');

      let getTaskTitleInput = document.getElementById('task');

      getTaskTitleInput.addEventListener('input', function () {

        let getTaskTitleInputValue = this.value;

        if (getTaskTitleInputValue == "") {
          $_getValidationField[0].innerHTML = 'Title Required';
          $_getValidationField[0].style.display = 'block';
        } else {
          $_getValidationField[0].style.display = 'none';
        }
      });

      let getTaskDescriptionInput = document.getElementById('taskdescription');

      getTaskDescriptionInput.addEventListener('input', function () {

        let getTaskDescriptionInputValue = this.value;

        if (getTaskDescriptionInputValue == "") {
          $_getValidationField[1].innerHTML = 'Description Required';
          $_getValidationField[1].style.display = 'block';
        } else {
          $_getValidationField[1].style.display = 'none';
        }

      })
    }
  }
</script>

<style>

</style>