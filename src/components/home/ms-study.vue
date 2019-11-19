<template> 
    <div class="ms-study">
        <div class="ms-study-title">
            <h2>Bạn sẽ học được gì?</h2>
        </div>
        <div class="ms-study-description">
            <p>
                Đến với cộng đồng CodersX không những bạn được học về lập trình miễn phí, 
                bạn còn có cơ hội thực tập với những dự án thực tế, có cơ hội được giới 
                thiệu tới các công ty lớn tại Nhật Bản.
            </p>
        </div>
        <div class="ms-study-content">
            <ul>
                <li>
                    <div class="ms-study-content-text">
                        <div class="ms-study-content-number">
                            <p>1</p>
                        </div>
                        <h4>Học lập trình cơ bản</h4>
                        <p>
                            Bạn sẽ được làm quen với ngôn ngữ lập trình JavaScript, 
                            các ngôn ngữ khác phục vụ cho lập trình web như HTML, CSS.
                        </p>
                    </div>
                </li>
                <div class="ms-study-content-text">
                    <h4>Học lập trình cơ bản</h4>
                    <p>
                        Bạn sẽ được làm quen với ngôn ngữ lập trình JavaScript, 
                        các ngôn ngữ khác phục vụ cho lập trình web như HTML, CSS.
                    </p>
                </div>
                <div class="ms-study-content-text">
                    <h4>Học lập trình cơ bản</h4>
                    <p>
                        Bạn sẽ được làm quen với ngôn ngữ lập trình JavaScript, 
                        các ngôn ngữ khác phục vụ cho lập trình web như HTML, CSS.
                    </p>
                </div>
                <div class="ms-study-content-text">
                    <h4>Học lập trình cơ bản</h4>
                    <p>
                        Bạn sẽ được làm quen với ngôn ngữ lập trình JavaScript, 
                        các ngôn ngữ khác phục vụ cho lập trình web như HTML, CSS.
                    </p>
                </div>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .ms-study {
        width: 100vw;
        border-top: 1px solid #ebebeb;
        margin: 0;
        padding: 0;
        right: 0;
        left: 0;
        padding-top: 25vh;
        background-color: #fafafa;

        .ms-study-title {
            display: flex;
            justify-content: center;
            font-family: sans-serif;

            h2 {
                font-size: 2.5em;
                font-weight: 300;
                margin: 0 auto;
            }

        }

        .ms-study-description {

            p {
                width: 61vw;
                line-height: 1.68421053em;
                font-size: 1.5em;
                color: #808080;
                margin: 0 auto;
                margin-top: 5vh;
            }
            
        }

        .ms-study-content {

            .ms-study-content-number {

                p {
                    width: 50px;
                    height: 50px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    border: 2px solid blue;
                    border-radius: 50%;
                    background-color: #fff;
                }
            }

            width: 26vw;
            display: flex;
            justify-content: center;
            flex-direction: column;

            h4 {
                font-weight: 300;
                font-size: 1.7em;
            }

            p {
                color: #666666;
                font-size: 1.3em;
            }


        }


    }
</style>